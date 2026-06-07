# Flüssigseife Beratung Projekt (Klassisches Organigramm)

```mermaid
graph TD
    %% تعريف الألوان والتنسيقات %%
    classDef main fill:#1E3A8A,color:#fff,stroke:#0F172A,stroke-width:3px;
    classDef level2 fill:#3B82F6,color:#fff,stroke:#1D4ED8,stroke-width:2px;
    classDef level3 fill:#E0F2FE,color:#000,stroke:#3B82F6,stroke-width:1px;

    %% المستوى الأول: العنوان الرئيسي في القمة %%
    Main[flüssigseife-Beratung-Ich]:::main

    %% المستوى الثاني: العناوين الخمسة الزرقاء تتفرع أفقياً تحت الرئيسي %%
    Main --> M1[1. Rechtliche Voraussetzungen]:::level2
    Main --> M2[2. Technische Voraussetzungen]:::level2
    Main --> M3[3. Genehmigungen / Zulassungen]:::level2
    Main --> M4[4. Fachliche Erfahrung]:::level2
    Main --> M5[5. Marketing]:::level2

    %% ----------------------------------------------------------------- %%
    %% 1. القسم الأول: البنود تصطف عمودياً تحت العنوان الأزرق الأول %%
    M1 --> M1_1[Gewerbeanmeldung]:::level3
    M1_1 --> M1_2[Rechtsformwahl & Handelsregister]:::level3
    M1_2 --> M1_3[Betriebshaftpflichtversicherung]:::level3
    M1_3 --> M1_4[Einhaltung der EU-Kosmetikverordnung]:::level3
    M1_4 --> M1_5[Steuerliche Erfassung beim Finanzamt]:::level3
    M1_5 --> M1_6[Datenschutz-Grundverordnung - DSGVO]:::level3

    %% ----------------------------------------------------------------- %%
    %% 2. القسم الثاني: البنود تصطف عمودياً تحت العنوان الأزرق الثاني %%
    M2 --> M2_1[GMP-gerechte Laborräume]:::level3
    M2_1 --> M2_2[Misch- und Rührtechnologie]:::level3
    M2_2 --> M2_3[Abfüll- und Verpackungsanlagen]:::level3
    M2_3 --> M2_4[Laborprüfgeräte für QC]:::level3
    M2_4 --> M2_5[Lagerung von Gefahrstoffen]:::level3
    M2_5 --> M2_6[Lüftungs- und Wassersysteme]:::level3

    %% ----------------------------------------------------------------- %%
    %% 3. القسم الثالث: البنود تصطف عمودياً تحت العنوان الأزرق الثالث %%
    M3 --> M3_1[CPNP-Portal Produktnotifizierung]:::level3
    M3_1 --> M3_2[Sicherheitsbewertung durch Experten]:::level3
    M3_2 --> M3_3[Freigabe durch das Umweltamt]:::level3
    M3_3 --> M3_4[Zulassung der Produktionsstätte]:::level3
    M3_4 --> M3_5[Zertifizierung nach ISO 22716]:::level3
    M3_5 --> M3_6[Bauaufsichtliche Genehmigung]:::level3

    %% ----------------------------------------------------------------- %%
    %% 4. القسم الرابع: البنود تصطف عمودياً تحت العنوان الأزرق الرابع %%
    M4 --> M4_1[Chemische Fachkenntnisse]:::level3
    M4_1 --> M4_2[Erfahrung in Rezepturentwicklung]:::level3
    M4_2 --> M4_3[Qualitätsmanagement-Erfahrung]:::level3
    M4_3 --> M4_4[Kenntnisse der Sicherheitsdatenblätter]:::level3
    M4_4 --> M4_5[Schulung in GMP-Richtlinien]:::level3
    M4_5 --> M4_6[Erfahrung mit Chargenprotokollen]:::level3

    %% ----------------------------------------------------------------- %%
    %% 5. القسم الخامس: البنود تصطف عمودياً تحت العنوان الأزرق الخامس %%
    M5 --> M5_1[Marktanalyse & Zielgruppenfokus]:::level3
    M5_1 --> M5_2[Branding & Corporate Identity]:::level3
    M5_2 --> M5_3[Rechtssichere Etikettierung]:::level3
    M5_3 --> M5_4[B2B-Vertriebsstrategie]:::level3
    M5_4 --> M5_5[Website & Online-Präsenz]:::level3
    M5_5 --> M5_6[Produkt-Launch-Kampagne]:::level3
