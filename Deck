import java.util.*;
import java.io.*;

public class Deck
{
	private Queue<Card> deck;

	public Deck()
	{
		deck = new LinkedList<Card>();
		for (int i = 0; i < 13; i++)
		{
			Card c = new Card("Red", i);
			Card c2 = new Card("Yellow", i);
			Card c3 = new Card("Green", i);
			Card c4 = new Card("Blue", i);
			deck.add(c);
			deck.add(c2);
			deck.add(c3);
			deck.add(c4);
		}
		for (int i = 13; i < 15; i++)
		{
			Card c = new Card("Black", i);
			Card c2 = new Card("Black", i);
			deck.add(c);
			deck.add(c2);
		}

		shuffle();

	}

	public Card deal()
	{
		Card c = deck.remove();
		deck.add(c);
		return c;
	}

	public void shuffle()
	{
		Collections.shuffle(deck);
	}

}
