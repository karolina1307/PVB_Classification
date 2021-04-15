# PVB_Classification

Klasifikace komorových extrasystol za použití hluboké neuronové sítě. 

Soubor ECG_filtering obsahuje kód pro základní předzpracování a filtraci signálů, které se následně uloží do souboru ve vhodném formátu (pickle) pro snadnější a rychlejší použití v dalších krocích kódu. 

Soubor PVB_Classification_v2 obsahuje hlavní část kódu - výběr vhodných signálů, jejich rozložení do train/val/test množin, augmentaci dat, trénování sítě, různé vizualizace, evaluaci hyperparametrů, Bayesovskou optimalizaci hyperparametrů a také výstupy CAM. 
