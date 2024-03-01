Místo pro jednoduché pokusy s různými lokálně běžícími velkými jazykovými modely o velikostech 7B a 13B. Zkoušíme převážně to, jak použitelné jsou při práci s českým jazykem a v českém kulturním prostředí.

První dojmy:

- ```mistral-openorca``` se ze všech nejvíc blíží použitelnému-ish stavu (rozuměj: rozumí, píše a přemýšlí cca jako děcko z prvního stupně, tedy s velkými chybami, ale relativně smysluplně, takže stojí za experimentální nasazení například při strojových rešerších velkých objemů textu)

- ```llama``` a ```phi``` jsou (alespoň v defaultním nastavení) mega lol (u druhého zmíněného to jde pochopit, má hlavně programovat)

To-do:

- Napsat jednotnou funkci pro běh experimentů a výsledky vedle vypisování v sešitech ukládat do JSONu.

- Vydestilovat sadu opravdu vypovídajících otázek.

- Doplnit benchmarkem z GPT-4. (Ono na tom totiž v některých našich úkolech taky není nejlíp.)
