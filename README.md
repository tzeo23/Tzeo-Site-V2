<!DOCTYPE html>
<html lang="el">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Μουσείο Teriade | Μυτιλήνη</title>
    <meta
      name="description"
      content="Επαγγελματική ιστοσελίδα παρουσίασης για το Μουσείο - Βιβλιοθήκη Στρατή Ελευθεριάδη Teriade στη Βαρειά Μυτιλήνης."
    />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Manrope:wght@400;500;600;700;800&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="page-shell">
      <header class="topbar">
        <a class="brand" href="#top" aria-label="Μουσείο Teriade">
          <span class="brand-mark">T</span>
          <span class="brand-copy">
            <strong>Μουσείο Teriade</strong>
            <span>Μυτιλήνη, Λέσβος</span>
          </span>
        </a>

        <button class="menu-toggle" id="menuToggle" aria-expanded="false" aria-controls="siteNav" aria-label="Άνοιγμα μενού">
          <i data-lucide="menu"></i>
        </button>

        <nav class="site-nav" id="siteNav" aria-label="Κύρια πλοήγηση">
          <a href="#museum">Το μουσείο</a>
          <a href="#collection">Η συλλογή</a>
          <a href="#visit">Επίσκεψη</a>
          <a href="#contact">Επικοινωνία</a>
        </nav>
      </header>

      <main id="top">
        <section class="hero">
          <div class="hero-media">
            <img
              src="https://www.visitlesvos.gr/wp-content/uploads/2023/04/DM_MOUS_VIVLIOTHIKI_STRATI_ELEUTHERIADI_TERIADE_01.jpg"
              alt="Εξωτερική όψη του Μουσείου Teriade στη Βαρειά Μυτιλήνης"
            />
          </div>
          <div class="hero-overlay"></div>
          <div class="hero-content">
            <p class="eyebrow">Στρατής Ελευθεριάδης - Teriade</p>
            <h1>Ένας τόπος όπου το βιβλίο, η ζωγραφική και η Μυτιλήνη συναντιούνται.</h1>
            <p class="hero-text">
              Στη Βαρειά της Μυτιλήνης, το Μουσείο - Βιβλιοθήκη Teriade φιλοξενεί το πλήρες εκδοτικό έργο του
              μεγάλου τεχνοκριτικού και εκδότη, μαζί με έργα και εκδόσεις που συνδέουν τον Picasso, τον Matisse,
              τον Chagall και τον Θεόφιλο με μια από τις πιο ξεχωριστές πολιτιστικές ιστορίες του Αιγαίου.
            </p>
            <div class="hero-actions">
              <a class="button button-primary" href="#visit">
                <i data-lucide="map-pinned"></i>
                <span>Οργάνωσε επίσκεψη</span>
              </a>
              <a class="button button-secondary" href="#collection">
                <i data-lucide="book-open"></i>
                <span>Ανακάλυψε τη συλλογή</span>
              </a>
            </div>
          </div>
        </section>

        <section class="intro-band">
          <article class="intro-card">
            <span class="stat">1979</span>
            <p>Το μουσείο άνοιξε για το κοινό τον Αύγουστο του 1979 και παραμένει ένα μοναδικό σημείο αναφοράς.</p>
          </article>
          <article class="intro-card">
            <span class="stat">Verve & Grand Livres</span>
            <p>Η καρδιά της συλλογής περιλαμβάνει το εκδοτικό σύμπαν του Teriade, σπάνιο και διεθνώς αναγνωρισμένο.</p>
          </article>
          <article class="intro-card">
            <span class="stat">Βαρειά</span>
            <p>Λίγα λεπτά από το κέντρο της Μυτιλήνης, σε ένα τοπίο ελαιώνα που δίνει στο μουσείο τη δική του ηρεμία.</p>
          </article>
        </section>

        <section class="section story-section" id="museum">
          <div class="section-heading">
            <p class="eyebrow">Το μουσείο</p>
            <h2>Η κληρονομιά του Teriade σε έναν χώρο που μοιάζει με ανοιχτό βιβλίο.</h2>
          </div>
          <div class="story-grid">
            <div class="story-copy">
              <p>
                Ο Στρατής Ελευθεριάδης - Teriade γεννήθηκε στη Μυτιλήνη το 1897 και έζησε στο Παρίσι, όπου
                αναδείχθηκε σε μία από τις πιο επιδραστικές μορφές της καλλιτεχνικής έκδοσης του 20ού αιώνα.
              </p>
              <p>
                Στο μουσείο παρουσιάζεται το σύνολο του εκδοτικού του έργου: τεύχη του <em>Verve</em>, αντίτυπα των
                <em>Grand Livres</em>, λιθογραφίες και σπάνιες συνεργασίες με κορυφαίους δημιουργούς της μοντέρνας
                τέχνης.
              </p>
              <p>
                Δεν είναι απλώς ένας εκθεσιακός χώρος. Είναι ένα ήσυχο πολιτιστικό καταφύγιο που αποκαλύπτει πώς η
                λέξη, η εικόνα και η τυπογραφία μπορούν να μετατραπούν σε έργο τέχνης.
              </p>
            </div>
            <aside class="info-panel">
              <div class="info-row">
                <i data-lucide="landmark"></i>
                <div>
                  <strong>Μοναδικότητα</strong>
                  <span>Σπάνια πλήρης παρουσίαση του εκδοτικού έργου του Teriade σε διεθνές επίπεδο.</span>
                </div>
              </div>
              <div class="info-row">
                <i data-lucide="palette"></i>
                <div>
                  <strong>Καλλιτέχνες</strong>
                  <span>Chagall, Picasso, Matisse, Léger και άλλοι συνδιαλέγονται μέσα από τις εκδόσεις.</span>
                </div>
              </div>
              <div class="info-row">
                <i data-lucide="graduation-cap"></i>
                <div>
                  <strong>Δράσεις</strong>
                  <span>Το μουσείο φιλοξενεί εκθέσεις, παρουσιάσεις και εκπαιδευτικά προγράμματα.</span>
                </div>
              </div>
            </aside>
          </div>
        </section>

        <section class="section gallery-section" id="collection">
          <div class="section-heading">
            <p class="eyebrow">Η συλλογή</p>
            <h2>Μια εμπειρία αφιερωμένη στις εκδόσεις τέχνης, τη μοντέρνα ευαισθησία και τον διάλογο με τον Θεόφιλο.</h2>
          </div>
          <div class="gallery-grid">
            <article class="feature-card feature-card-large">
              <img
                src="https://www.visitlesvos.gr/wp-content/uploads/2023/04/DM_MOUS_VIVLIOTHIKI_STRATI_ELEUTHERIADI_TERIADE_02.jpg"
                alt="Εσωτερικός χώρος του Μουσείου Teriade με εκθέματα"
              />
              <div class="feature-copy">
                <h3>Το εκδοτικό έργο ως έκθεμα</h3>
                <p>
                  Στο Teriade, τα βιβλία δεν λειτουργούν ως απλά τεκμήρια. Παρουσιάζονται σαν ζωντανά αντικείμενα
                  τέχνης, όπου η τυπογραφία, το χαρτί και η εικονογράφηση αποκτούν μουσειακή παρουσία.
                </p>
              </div>
            </article>

            <article class="feature-card">
              <div class="icon-badge"><i data-lucide="layers-3"></i></div>
              <h3>Verve</h3>
              <p>Το ιστορικό περιοδικό που ένωσε εικαστικούς και λογοτέχνες σε μια πρωτοποριακή εκδοτική γλώσσα.</p>
            </article>

            <article class="feature-card">
              <div class="icon-badge"><i data-lucide="brush"></i></div>
              <h3>Grand Livres</h3>
              <p>Πολυτελείς εικονογραφημένες εκδόσεις, χειροποίητες και περιορισμένες, με κορυφαίες συνεργασίες.</p>
            </article>

            <article class="feature-card">
              <div class="icon-badge"><i data-lucide="sparkles"></i></div>
              <h3>Θεόφιλος</h3>
              <p>Η σχέση του Teriade με τον Θεόφιλο παραμένει κεντρική για την κατανόηση της ελληνικής λαϊκής ζωγραφικής.</p>
            </article>
          </div>
        </section>

        <section class="section visit-section" id="visit">
          <div class="visit-layout">
            <div>
              <p class="eyebrow">Επίσκεψη</p>
              <h2>Ένας προορισμός πολιτισμού δίπλα στην πόλη, μέσα στο τοπίο της Βαρειάς.</h2>
              <p class="visit-lead">
                Το μουσείο βρίσκεται στη Βαρειά, νότια της Μυτιλήνης, σε κοντινή απόσταση από το κέντρο της πόλης και
                σε γειτονία με το Μουσείο Θεόφιλου.
              </p>
            </div>

            <div class="visit-cards">
              <article class="visit-card">
                <i data-lucide="map-pin"></i>
                <div>
                  <h3>Διεύθυνση</h3>
                  <p>Βαρειά, 81150, Μυτιλήνη Λέσβου</p>
                </div>
              </article>
              <article class="visit-card">
                <i data-lucide="phone"></i>
                <div>
                  <h3>Τηλέφωνα</h3>
                  <p>22510 23372<br />22510 42855</p>
                </div>
              </article>
              <article class="visit-card">
                <i data-lucide="mail"></i>
                <div>
                  <h3>Email</h3>
                  <p><a href="mailto:info@museumteriade.gr">info@museumteriade.gr</a></p>
                </div>
              </article>
              <article class="visit-card">
                <i data-lucide="clock-3"></i>
                <div>
                  <h3>Ωράριο</h3>
                  <p>Για τρέχουσες ημέρες και ώρες λειτουργίας, συνιστάται επικοινωνία με το μουσείο πριν την επίσκεψη.</p>
                </div>
              </article>
            </div>
          </div>
        </section>

        <section class="section quote-section">
          <div class="quote-shell">
            <p class="eyebrow">Γιατί αξίζει</p>
            <blockquote>
              Ένας χώρος που δεν αφηγείται μόνο τη ζωή ενός μεγάλου εκδότη, αλλά την ίδια τη στιγμή όπου το βιβλίο έγινε
              φορέας μοντέρνας τέχνης.
            </blockquote>
          </div>
        </section>

        <section class="section contact-section" id="contact">
          <div class="contact-card">
            <div>
              <p class="eyebrow">Επικοινωνία</p>
              <h2>Σχεδίασε την επόμενη πολιτιστική σου στάση στη Μυτιλήνη.</h2>
              <p>
                Για πληροφορίες σχετικά με πρόσβαση, ομαδικές επισκέψεις ή εκπαιδευτικές δράσεις, η άμεση επικοινωνία με
                το μουσείο είναι ο καλύτερος τρόπος για μια σωστά οργανωμένη εμπειρία.
              </p>
            </div>
            <div class="contact-actions">
              <a class="button button-primary" href="http://www.museumteriade.gr/" target="_blank" rel="noreferrer">
                <i data-lucide="globe"></i>
                <span>Επίσημη ιστοσελίδα</span>
              </a>
              <a class="button button-secondary" href="mailto:info@museumteriade.gr">
                <i data-lucide="send"></i>
                <span>Στείλε email</span>
              </a>
            </div>
          </div>
        </section>
      </main>

      <footer class="site-footer">
        <p>Μουσείο - Βιβλιοθήκη Στρατή Ελευθεριάδη Teriade</p>
        <p>Μυτιλήνη, Λέσβος</p>
      </footer>
    </div>

    <script src="https://unpkg.com/lucide@latest"></script>
    <script src="./app.js"></script>
  </body>
</html>
