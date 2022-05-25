Cards:

1) Working implementation of a standard deck of playing cards

2) Rap, Texas Hold 'Em

---

- playing cards
    - 52 cards
        - 4 `suits` of 13 `faces`
        - suits
            - diamonds
            - hearts
            - spades
            - clubs
        - faces
            - (2 through 10) + (jack, queen, king, ace)
            - 0 - 12
- implementation
    - [X] Make one card
        - [ ] display mechanism for card
            - given a card (a object of `class` Card), show the user a meaningful representation
    - [ ] Deck Cards 
        - [ ] Shuffle the decks
        - [X] Make a deck of cards
    - [ ] Hand
        - make a hand section
            - make a card
            - make a card DOM element with suit + face
            - attach DOM element to hand
            - attach hand somewhere

            - Make texas hold 'em
                - 1) model hands hierarchically
                - 2) dealing cards
                    - shuffle 
                        - putting cards in a random order
                        - array of 52 cards
                            { face: number, suit: string}
                        - algorithms
                            - pick and stick
                                - pop card from first deck
                                - place card in random index of second deck
                                - if index is occupied
                                    - put it in the next available
                    - deal
                    - flop (x3)
                    - Turn (1)
                    - River (1)
                - 3)Implement the betting