# Textová adventura: Běžný den

Jednoduchá interaktivní textová hra napsaná v Pythonu. Hráč se probudí ve svém pokoji a musí čelit nástrahám "běžného" dne. Vaším cílem je úspěšně se obléknout, vyhnout se problémům v práci, případně si vybrat peníze a nakoupit. Hra obsahuje systém inventáře, vtipné dialogy a různé cesty, jak příběh prozkoumat.

## 🎮 O hře

Hra funguje na principu stavového automatu, kde se hráč pohybuje mezi různými "pokoji" (scénami) pomocí číselných voleb. Každá lokace nabízí jiné možnosti a některé akce vyžadují, abyste splnili určité podmínky (například mít u sebe peníze nebo nebýt v pyžamu).

**Klíčové prvky:**
* **Inventář:** Sbírejte předměty jako oblečení (`p`), batoh (`b`) nebo peníze (`m`).
* **Paměť na PIN:** Na začátku hry zadáte PIN kód. Dobře si ho zapamatujte, budete ho potřebovat u bankomatu!
* **Peníze (Peněženka):** Získejte peníze a rozhodněte se, zda je dáte bezdomovci.
* **Vtipné scénáře:** Čeká vás setkání se šéfem, který vás vyhodí, nebo zjištění, že jít do Lidlu v pyžamu není ten nejlepší nápad.

## ⚙️ Požadavky

* Ke spuštění hry stačí mít nainstalovaný **Python 3.x**. Žádné externí knihovny nejsou potřeba.

## 🚀 Jak hru spustit

1. Stáhněte si zdrojový kód do souboru (např. `hra.py`).
2. Otevřete terminál nebo příkazovou řádku.
3. Přejděte do složky, kde je soubor uložen.
4. Spusťte hru příkazem:
   ```bash
   python hra.py