# Review Mood Checker (Android)

Type a restaurant review and the app says whether it is **Positive (1)** or **Negative (0)**.

It uses the classic NLP pipeline from class: raw text → preprocess (lowercase, clean, tokenise, keep negations) → TF-IDF features → Logistic Regression → output.
The model is trained on the UCI *Sentiment Labelled Sentences* Yelp file (Kotzias et al., 2015, CC BY 4.0) every time the app opens.

## Get the app
1. Open the **Releases** section of this repo on your Android phone.
2. Download `MoodChecker.apk` and open it.
3. If Android asks, allow installing from this source.

GitHub Actions builds a new APK automatically on every push to `main` (see `.github/workflows/build-apk.yml`).
