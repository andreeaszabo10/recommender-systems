# recommender-systems
Am ales domeniul filmelor pentru ca m-a pasionat de mult timp, fiind si tema licentei mele. Filmele au mai multe genuri, rating-uri si descrieri care ajuta in oferirea unor recomandari personalizate.

Datasetul ales poate fi gasit la link ul: https://www.kaggle.com/datasets/figolm10/movie-dataset?resource=download si am folosit 3999 intrari. Am ales atatea pentru a nu aglomera datasetul prea tare si am sters randuri care nu corespundeau cu coloanele sau care nu aveau genuri adaugate, deoarece ar fi facut recomandarile mai complicate.

Din acesta am ales sa pastrez 12 coloane, toate fiind importante pentru recomandarea unui film: 
- de tip string: genres, homepage, overview, title, tagline, cast, director si keywords.
- de tip double: vote_average, vote_count, runtime, popularity.

Ulterior am adaugat o noua coloana numita id, unde am creat un id unic pentru fiecare film cu formula row()-1 in excel. Coloana cu id lipsea din dataset initial deoarece am crezut ca se adauga automat in recombee si nu este necesara. Am sters doua intrari din dataset in plus, acum ramanand 3997, pentru ca nu corespundeau cu coloanele datasetului.

Toate datele din dataset au fost incarcate cu succes in recombee.
