# guac

#generate random sentences

cat Top.gr S1.gr S1_Vocab.gr S2.gr S2_Vocab.gr > GRAMMAR.gr

./randsent GRAMMAR.gr (#) (-t) (--seed #)

#(on athena) test grammaticality of test sentences; -s S1 uses S1 as start symbol
# Setup 6.863 first

cat S1.gr S1_Vocab.gr > S1GR.gr

/mit/6.863/spring2018/Software/parse -g S1GR.gr -i base-set.sen -s S1


Recipe
    Ingredients
        2 ripe avocados
        1/2 teaspoon Kosher salt
        1 Tbsp of fresh lime juice or lemon juice
        2 Tbsp to 1/4 cup of minced red onion or thinly sliced green onion
        1-2 serrano chiles, stems and seeds removed, minced
        2 tablespoons cilantro (leaves and tender stems), finely chopped
        A dash of freshly grated black pepper
        1/2 ripe tomato, seeds and pulp removed, chopped

    Cut avocado, remove flesh: Cut the avocados in half. Remove seed. Score the inside of the avocado with a blunt knife and scoop out the flesh with a spoon. Place in a bowl.

    Mash with a fork: Using a fork, roughly mash the avocado.

    Add salt, lime juice, and the rest: Sprinkle with salt and lime (or lemon) juice. Add the chopped onion, cilantro, black pepper, and chiles.
