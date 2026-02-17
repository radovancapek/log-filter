## spusteni skriptu pro hodinove statistiky:

	node log-filter.mjs --file log-2025-03-05.log --hour 13

## spusteni skriptu pro filtrovani:

	node log-filter.mjs --file log-2025-03-05.log --service warehouse-service --user user-1334

Výstup statistik je přímo v konzoli a filtrovaní je zapsáno do souboru output.log a nebo do parametrem určeného souboru (--out <soubor>)


Předpokládal jsem testovací spouštění nad konkrétním logem.
Čas je v kódu na tvrdo na míru tomu testovacímu logu.
