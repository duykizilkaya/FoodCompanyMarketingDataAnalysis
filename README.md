# Food Marketing Data Analysis Project

** German Below


This project involves the comprehensive analysis of marketing data from a food company. The primary objective is to gain insights into customer behavior, spending patterns, and responses to various marketing campaigns to optimize future marketing strategies.

## Project Overview

### Goals:

* Data Cleaning and Transformation: Prepare the data for analysis by handling missing values, converting data types, normalizing columns, dealing with outliers, and renaming columns for better readability.
* Descriptive Analysis: Summarize the main features of the dataset, including customer demographics, their spending habits, and their responses to campaigns to understand the overall data distribution.
* Exploratory Analysis: Use visual and statistical techniques to uncover patterns, correlations, and trends within the data, providing a deeper understanding of customer behavior.
* Visual Analysis: Create visualizations to illustrate key trends and patterns in the data, making it easier to interpret and communicate findings.
* Statistical Analysis: Conduct statistical tests, such as chi-square tests and point-biserial correlations, to validate findings and uncover deeper insights.
* Actionable Insights: Generate actionable insights and recommendations based on the analysis to improve marketing strategies and customer targeting.

### Achievements:

* Cleaned and transformed the dataset for effective analysis.
* Generated a variety of visualizations to illustrate key insights.
* Performed statistical analyses, including chi-square tests and point-biserial correlations, to support findings.

### Results:

_Visual Results_:

The project includes several visualizations to highlight key findings. Here are some examples below:

* Proportion of response to the last campaign
![download](https://github.com/user-attachments/assets/cd3aebb0-2c43-40ce-ab3f-736a49b899ae)

* Proportion of total acceptance of campaigns by marital status
![download](https://github.com/user-attachments/assets/e650ecb8-1ddd-414c-9f92-1032ee3135cc)

   * Marital Status vs Total Acceptance of Campaigns:
      * No significant relationship was found (p-value: 0.3405).
   * Marital Status vs Response to the Last Campaign:
     * A significant relationship was found (p-value: 4.06e-10).

* Proportion of total acceptance of campaigns by education level
![download](https://github.com/user-attachments/assets/4de94b4a-8022-4464-b8ce-6629ef66fe8b)

    * Education Level vs Total Acceptance of Campaigns:
      * No significant relationship was found (p-value: 0.1502).
   * Education Level vs Response to the Last Campaign:
      * A significant relationship was found (p-value: 8.02e-05).

* Proportion of positive responses to the last campaign by age
![download](https://github.com/user-attachments/assets/63bf5fb7-d560-4a37-aeba-4729bfec58a3)

   * Age vs Response to the Last Campaign:
      * No significant relationship was found (correlation: -0.0199, p-value: 0.3501).
   * Age vs Total Acceptance of Campaigns:
      * No significant relationship was found (correlation: -0.0058, p-value: 0.7859).

* Proportion of positive responses to the last campaign by income
![download](https://github.com/user-attachments/assets/912eca3a-79b8-47c1-9193-4d62e066ea88)

   * Yearly Income vs Total Acceptance of Campaigns:
      * A significant relationship was found (correlation: -0.006, p-value: 0.7859).

* Proportion of complaints for the last two years
![download](https://github.com/user-attachments/assets/f84c0e3e-c027-41b1-a12d-af07fde30a1c)

* Number of purchases from deals for different income levels, split by whether the customer has complaints
![download](https://github.com/user-attachments/assets/5a96041a-ff67-4915-84d3-d5dc63bf101e)

   * Customer Tenure vs Response to the Last Campaign:
      * A significant positive correlation was found (correlation: 0.1957, p-value: 1.86e-20).

* Relationship between purchases made with discount and directly in store
![download](https://github.com/user-attachments/assets/05159312-b0b7-4aeb-a926-fd999c7a5947)

* Relationship between yearly income and purchases directly made in store
![download](https://github.com/user-attachments/assets/5536c569-7de5-4eca-90dc-ecb451eedf15)

* Correlation Map by using Heatmap
![download](https://github.com/user-attachments/assets/bcfa3937-3232-422b-8950-5740569d1c56)

* Normal distribution of online purchases by using Box-Cox
![download](https://github.com/user-attachments/assets/8af991ad-cee6-4600-bba1-c485af9559c3)

### Key Findings

* Customer Demographics: The majority of customers are middle-aged, with a significant portion of customers aged between 35 and 55. Income distribution shows that most customers earn between $30,000 and $60,000 annually.

* Spending Patterns: Customers spend the most on wines, followed by meat products. This indicates a preference for these categories. Spending habits vary significantly across different education levels and marital statuses.

* Campaign Responses: Response rates to the last campaign vary by marital status and education level, with married and higher-educated individuals showing more positive responses.

### Conclusion

The analysis of the food marketing data has provided several valuable insights that can inform future marketing strategies:

* Target High-Spending Categories: Focus marketing efforts on promoting wines and meat products, as these are the categories with the highest customer spending.

* Segmented Marketing Campaigns: Tailor marketing campaigns based on marital status and education level, as these factors significantly influence campaign responses. For instance, campaigns targeting married and higher-educated individuals are likely to be more effective.

* Customer Engagement: Invest in strategies to engage long-tenure customers, as they show a positive response to campaigns. Loyalty programs or exclusive offers could be effective.

* Addressing Customer Complaints: Implement measures to reduce customer complaints, as dissatisfaction significantly affects campaign responses. Improved customer service and prompt resolution of issues are essential.

* Income-Based Marketing: Although yearly income showed mixed results in terms of campaign acceptance, higher-income customers are generally more responsive. Consider premium offerings and exclusive deals for higher-income segments.

* Age Consideration: While age did not show a significant impact on campaign responses, it is still useful to consider age-specific preferences when designing product offerings and marketing messages.

By leveraging these insights, the food company can optimize its marketing strategies, improve customer satisfaction, and increase overall campaign effectiveness. The combination of descriptive, exploratory, and statistical analyses has provided a comprehensive understanding of customer behavior and preferences, which is crucial for making informed marketing decisions.

** This data set was retrieved from GitHub and found in Kaggle: https://github.com/nailson/ifood-data-business-analyst-test
https://www.kaggle.com/datasets/jackdaoud/marketing-data
** In this project, pandas, matplotlib, seaborn, numpy, scipy and datetime modules were imported and used in Python language. 

# Lebensmittel-Marketing-Datenanalyse-Projekt

Dieses Projekt umfasst die umfassende Analyse von Marketingdaten eines Lebensmittelunternehmens. Das Hauptziel ist es, Einblicke in das Kundenverhalten, Ausgabemuster und Reaktionen auf verschiedene Marketingkampagnen zu gewinnen, um zukünftige Marketingstrategien zu optimieren.

## Projektübersicht

### Ziele:

* Datenbereinigung und -transformation: Vorbereitung der Daten für die Analyse durch Behandlung fehlender Werte, Konvertierung von Datentypen, Normalisierung von Spalten, Umgang mit Ausreißern und Umbenennung von Spalten für bessere Lesbarkeit.
* Deskriptive Analyse: Zusammenfassung der Hauptmerkmale des Datensatzes, einschließlich Kundendemografie, Ausgabegewohnheiten und Reaktionen auf Kampagnen, um die allgemeine Datenverteilung zu verstehen.
* Explorative Analyse: Verwendung visueller und statistischer Techniken, um Muster, Korrelationen und Trends innerhalb der Daten aufzudecken und ein tieferes Verständnis des Kundenverhaltens zu ermöglichen.
* Visuelle Analyse: Erstellung von Visualisierungen zur Veranschaulichung wichtiger Trends und Muster in den Daten, um die Interpretation und Kommunikation der Ergebnisse zu erleichtern.
* Statistische Analyse: Durchführung statistischer Tests wie Chi-Quadrat-Tests und punktbiseriale Korrelationen, um Erkenntnisse zu validieren und tiefere Einblicke zu gewinnen.
* Umsetzbare Erkenntnisse: Generierung von umsetzbaren Erkenntnissen und Empfehlungen basierend auf der Analyse zur Verbesserung von Marketingstrategien und Kundenzielgruppenansprache.

### Errungenschaften:

* Bereinigung und Transformation des Datensatzes für eine effektive Analyse.
* Erstellung einer Vielzahl von Visualisierungen zur Veranschaulichung wichtiger Erkenntnisse.
* Durchführung statistischer Analysen, einschließlich Chi-Quadrat-Tests und punktbiserialer Korrelationen, zur Unterstützung der Ergebnisse.

### Ergebnisse:

_Visuelle Ergebnisse_:

Das Projekt enthält mehrere Visualisierungen zur Hervorhebung wichtiger Erkenntnisse. Hier sind einige Beispiele:

* Anteil der Reaktionen auf die letzte Kampagne  
![download](https://github.com/user-attachments/assets/cd3aebb0-2c43-40ce-ab3f-736a49b899ae)

* Anteil der Gesamtakzeptanz von Kampagnen nach Familienstand  
![download](https://github.com/user-attachments/assets/e650ecb8-1ddd-414c-9f92-1032ee3135cc)

   * Familienstand vs. Gesamtakzeptanz von Kampagnen:
      * Es wurde kein signifikanter Zusammenhang gefunden (p-Wert: 0,3405).
   * Familienstand vs. Reaktion auf die letzte Kampagne:
     * Ein signifikanter Zusammenhang wurde gefunden (p-Wert: 4,06e-10).

* Anteil der Gesamtakzeptanz von Kampagnen nach Bildungsniveau  
![download](https://github.com/user-attachments/assets/4de94b4a-8022-4464-b8ce-6629ef66fe8b)

    * Bildungsniveau vs. Gesamtakzeptanz von Kampagnen:
      * Es wurde kein signifikanter Zusammenhang gefunden (p-Wert: 0,1502).
   * Bildungsniveau vs. Reaktion auf die letzte Kampagne:
      * Ein signifikanter Zusammenhang wurde gefunden (p-Wert: 8,02e-05).

* Anteil positiver Reaktionen auf die letzte Kampagne nach Alter  
![download](https://github.com/user-attachments/assets/63bf5fb7-d560-4a37-aeba-4729bfec58a3)

   * Alter vs. Reaktion auf die letzte Kampagne:
      * Es wurde kein signifikanter Zusammenhang gefunden (Korrelation: -0,0199, p-Wert: 0,3501).
   * Alter vs. Gesamtakzeptanz von Kampagnen:
      * Es wurde kein signifikanter Zusammenhang gefunden (Korrelation: -0,0058, p-Wert: 0,7859).

* Anteil positiver Reaktionen auf die letzte Kampagne nach Einkommen  
![download](https://github.com/user-attachments/assets/912eca3a-79b8-47c1-9193-4d62e066ea88)

   * Jährliches Einkommen vs. Gesamtakzeptanz von Kampagnen:
      * Ein signifikanter Zusammenhang wurde gefunden (Korrelation: -0,006, p-Wert: 0,7859).

* Anteil der Beschwerden in den letzten zwei Jahren  
![download](https://github.com/user-attachments/assets/f84c0e3e-c027-41b1-a12d-af07fde30a1c)

* Anzahl der Käufe aus Angeboten für verschiedene Einkommensstufen, aufgeteilt danach, ob der Kunde Beschwerden hat  
![download](https://github.com/user-attachments/assets/5a96041a-ff67-4915-84d3-d5dc63bf101e)

   * Kundendauer vs. Reaktion auf die letzte Kampagne:
      * Eine signifikante positive Korrelation wurde gefunden (Korrelation: 0,1957, p-Wert: 1,86e-20).

* Beziehung zwischen Käufen mit Rabatt und direkt im Geschäft  
![download](https://github.com/user-attachments/assets/05159312-b0b7-4aeb-a926-fd999c7a5947)

* Beziehung zwischen jährlichem Einkommen und direkt im Geschäft getätigten Käufen  
![download](https://github.com/user-attachments/assets/5536c569-7de5-4eca-90dc-ecb451eedf15)

* Korrelationskarte mittels Heatmap  
![download](https://github.com/user-attachments/assets/bcfa3937-3232-422b-8950-5740569d1c56)

* Normalverteilung der Online-Käufe mittels Box-Cox-Transformation  
![download](https://github.com/user-attachments/assets/8af991ad-cee6-4600-bba1-c485af9559c3)

### Wichtigste Erkenntnisse

* Kundendemografie: Die Mehrheit der Kunden ist mittleren Alters, wobei ein bedeutender Teil der Kunden zwischen 35 und 55 Jahre alt ist. Die Einkommensverteilung zeigt, dass die meisten Kunden jährlich zwischen 30.000 und 60.000 Dollar verdienen.

* Ausgabemuster: Kunden geben am meisten für Weine aus, gefolgt von Fleischprodukten. Dies deutet auf eine Präferenz für diese Kategorien hin. Die Ausgabegewohnheiten variieren erheblich zwischen verschiedenen Bildungsniveaus und Familienständen.

* Kampagnenreaktionen: Die Reaktionsraten auf die letzte Kampagne variieren je nach Familienstand und Bildungsniveau, wobei verheiratete und höher gebildete Personen positivere Reaktionen zeigen.

### Fazit

Die Analyse der Lebensmittel-Marketingdaten hat mehrere wertvolle Erkenntnisse geliefert, die zukünftige Marketingstrategien beeinflussen können:

* Fokussierung auf Kategorien mit hohen Ausgaben: Konzentration der Marketingbemühungen auf die Förderung von Weinen und Fleischprodukten, da dies die Kategorien mit den höchsten Kundenausgaben sind.

* Segmentierte Marketingkampagnen: Anpassung von Marketingkampagnen basierend auf Familienstand und Bildungsniveau, da diese Faktoren die Kampagnenreaktionen signifikant beeinflussen. Beispielsweise sind Kampagnen, die sich an verheiratete und höher gebildete Personen richten, wahrscheinlich effektiver.

* Kundenengagement: Investition in Strategien zur Einbindung langjähriger Kunden, da diese eine positive Reaktion auf Kampagnen zeigen. Treueprogramme oder exklusive Angebote könnten effektiv sein.

* Umgang mit Kundenbeschwerden: Implementierung von Maßnahmen zur Reduzierung von Kundenbeschwerden, da Unzufriedenheit die Kampagnenreaktionen erheblich beeinflusst. Verbesserter Kundenservice und schnelle Problemlösung sind wesentlich.

* Einkommensbasiertes Marketing: Obwohl das jährliche Einkommen gemischte Ergebnisse hinsichtlich der Kampagnenakzeptanz zeigte, sind Kunden mit höherem Einkommen im Allgemeinen ansprechbarer. Erwägen Sie Premium-Angebote und exklusive Deals für Segmente mit höherem Einkommen.

* Altersberücksichtigung: Obwohl das Alter keinen signifikanten Einfluss auf die Kampagnenreaktionen zeigte, ist es dennoch nützlich, altersspezifische Präferenzen bei der Gestaltung von Produktangeboten und Marketingbotschaften zu berücksichtigen.

Durch die Nutzung dieser Erkenntnisse kann das Lebensmittelunternehmen seine Marketingstrategien optimieren, die Kundenzufriedenheit verbessern und die Gesamteffektivität der Kampagnen erhöhen. Die Kombination aus deskriptiven, explorativen und statistischen Analysen hat ein umfassendes Verständnis des Kundenverhaltens und der Präferenzen geliefert, was für fundierte Marketingentscheidungen entscheidend ist.

** Dieser Datensatz wurde von GitHub abgerufen und auf Kaggle gefunden: https://github.com/nailson/ifood-data-business-analyst-test  
https://www.kaggle.com/datasets/jackdaoud/marketing-data
** In diesem Projekt wurden die Module pandas, matplotlib, seaborn, numpy, scipy und datetime importiert und in der Programmiersprache Python verwendet.



