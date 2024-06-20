#Spam Filter
Celem projektu jest nauczenie modelu klasyfikacji binarnej e-maili na spam oraz ham.
##Uruchomienie
Do uruchomienia modelu potrzebne są plik z kodem, zestaw danych oraz instalacja odpowiednich bilbiotek opisanych w pliku requirements.
## Opis modelu
Wykorzystuję funkcje WordNetLemmatizer do wstępnego formatowania danych. Sam model opiera się na LogisticRegression oraz formatowaniu przy użyciu TfidfVectorizer. Korzystając z GridSearchCV dobieramy optymalne parametry dla tych funkcji.
