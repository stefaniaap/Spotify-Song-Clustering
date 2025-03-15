Spotify Song Clustering  


## 📌 Περιγραφή  
Η παρούσα εργασία εστιάζει στην κατηγοριοποίηση των τραγουδιών από τη βάση δεδομένων του Spotify, εφαρμόζοντας τεχνικές μηχανικής μάθησης και συγκεκριμένα αλγόριθμους **clustering**.  


Στόχος είναι η ανάλυση χαρακτηριστικών όπως:  


- **Danceability**: Καταλληλότητα για χορό (ρυθμός, σταθερότητα, ένταση).  
- **Energy**: Ενέργεια του τραγουδιού (ένταση, ταχύτητα).  
- **Valence**: Συναισθηματικός τόνος (υψηλές τιμές → χαρούμενα τραγούδια, χαμηλές τιμές → λυπητερά).  
- **Tempo**: Ο ρυθμός του τραγουδιού (BPM).  
- **Popularity**: Δείκτης δημοφιλίας (αριθμός ακροάσεων & προτιμήσεις χρηστών).  


Η ανάλυση έχει πρακτικές εφαρμογές όπως:  
- Δημιουργία **αυτόματων playlists**.  
- **Σύσταση** τραγουδιών με βάση τα γούστα του χρήστη.  
- Ανίχνευση **μουσικών τάσεων**.  


## 🛠 Τεχνικές & Αλγόριθμοι  
Για την ομαδοποίηση των τραγουδιών, εφαρμόστηκαν οι εξής αλγόριθμοι **clustering**:  


- **K-Means Clustering**  
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**  
- **Affinity Propagation**  
- **Mean Shift**  
- **BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies)**  
- **OPTICS (Ordering Points To Identify the Clustering Structure)**  
- **Agglomerative Clustering**  
- **MiniBatch K-Means**  
- **Ward Clustering**  
- **Gaussian Mixture Model (GMM)**  


Επιπλέον, χρησιμοποιήθηκαν τεχνικές προεπεξεργασίας δεδομένων και **Principal Component Analysis (PCA)** για μείωση διάστασης και οπτικοποίηση αποτελεσμάτων.  


## 📊 Δεδομένα  
Το dataset που χρησιμοποιήθηκε είναι το **"Spotify Tracks Dataset"** από το **Kaggle**, το οποίο περιέχει πληροφορίες για τραγούδια του Spotify.  


Χαρακτηριστικά που αναλύθηκαν:  
- **Danceability**  
- **Energy**  
- **Valence**  
- **Tempo**  
- **Popularity**  


## 📂 Περιεχόμενα Repository  
- `Spotify_Clustering.ipynb`: Ανάλυση και εφαρμογή αλγορίθμων clustering.  
- `data_processing.ipynb`: Προεπεξεργασία και καθαρισμός δεδομένων.  
- `dataset.csv`: Το dataset που χρησιμοποιήθηκε.  
-`cleaned_dataset.csv`: Το καθαρό dataset που δημιουργήθηκε απο την προεπεξεργασία και  
   τον καθαρισμό δεδομένων. 
- `requirements.txt`: Λίστα με τις απαιτούμενες βιβλιοθήκες.  
- `graphs`: Αποτελέσματα και γραφήματα της ανάλυσης.