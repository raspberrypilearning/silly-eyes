## Εφέ αντικειμένου

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Μπορείς να κάνεις τον **χαρακτήρα** σου αντικείμενο και τα αντικείμενα **αστείο μάτι** να αλλάξουν `Όψεις`{:class="block3looks"} όταν κάνεις κλικ σε αυτά.
</div>
<div>

![Ένας χαρακτήρας και μάτια με εφέ γραφικών.](images/character-graphic-effects.png){:width="300px"}   

</div>
</div>

### Αστεία εφέ στα μάτια

--- task ---

Πρόσθεσε ένα μπλοκ `όταν γίνει κλικ σε αυτό το αντικείμενο`{:class="block3events"} στο αντικείμενό σου **Μάτι**.

Μπορείς να καταλάβεις ποιο μπλοκ κώδικα πρέπει να τοποθετήσεις από κάτω για να αλλάξεις το χρώμα των ματιών του αντικειμένου σου όταν κάνεις κλικ στο αντικείμενο **Μάτι**;

--- collapse ---
---
title: Άλλαξε εφέ γραφικών όταν κάνεις κλικ στο αντικείμενο
---

```blocks3
when this sprite clicked  
change [color v] effect by (25)
```

--- /collapse ---

--- /task ---

--- task ---

Εάν θέλεις και οι δύο βολβοί των ματιών να έχουν το ίδιο αποτέλεσμα, θα πρέπει να αντιγράψεις το script σου στο αντικείμενο **Μάτι 2**.

[[[scratch3-copy-code]]]

--- /task ---

### Εφέ χαρακτήρων

--- task ---

Κάνε κλικ στον **χαρακτήρα** στη λίστα αντικειμένων και στη συνέχεια, κάνε κλικ στην καρτέλα **Κώδικας**.

Πρόσθεσε το ίδιο script που χρησιμοποίησες για να αλλάξει το χρώμα των ματιών. Ποια εφέ γραφικών θέλεις να αλλάξεις για τον **χαρακτήρα** σου;

**Επιλογή:** Επίλεξε ένα εφέ από το μενού `άλλαξε εφέ χρώματος κατά`{:class="block3looks"}. Πειραματίσου με τους αριθμούς και τα εφέ μέχρι να έχεις μια αλλαγή που σου αρέσει.

[[[scratch3-graphic-effects]]]

--- /task ---

### Ένα αξεσουάρ

Τώρα, πρόσθεσε ένα **αξεσουάρ**, όπως ένα καπέλο, που αλλάζει όταν κάνεις κλικ πάνω του - χρησιμοποίησε το μπλοκ`επόμενη ενδυμασία`{:class="block3looks"}.

--- task ---

**Επίλεξε:** Πρόσθεσε αλλαγή αξεσουάρ ή αλλαγή ενδυμασίας της επιλογής σου.

![Αντικείμενα με αξεσουάρ.](images/accessory-sprite.png)

--- collapse ---
---
title: Κάνε μια αλλαγή ενδυμασίας στο αντικείμενο όταν κάνεις κλικ
---

**Gobo με αξεσουάρ ενδυμασιών**: [Δες μέσα](https://scratch.mit.edu/projects/496334057/editor){:target="_blank"}
<div class="scratch-preview">
<iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/496334057/?autostart=false" frameborder="0"></iframe>
</div>

Ορισμένα αντικείμενα έχουν ήδη τη δυνατότητα επιλογής από ενδυμασίες.

Μπορείς να προσθέσεις κώδικα για να κάνεις να αλλάξει η ενδυμασία στην`επόμενη ενδυμασία`{:class="block3looks"} όταν κάνεις κλικ στο αντικείμενο:

```blocks3
when this sprite clicked
next costume
```

--- /collapse ---

Εάν το αντικείμενό σου δεν έχει επιλογή ενδυμασιών ή θέλεις να προσθέσεις περισσότερες, μπορείς να προσθέσεις οποιαδήποτε ενδυμασία σε ένα αντικείμενο.

[[[scratch3-add-costumes-to-a-sprite]]]

--- /task ---

--- task ---

**Δοκιμή:** Δούλεψε τα αντικείμενά σου μέχρι να αλληλεπιδράσουν με τον τρόπο που θέλεις.

**Συμβουλή:** Κάνε μία αλλαγή τη φορά και έλεγξε τι κάνει, ώστε να μπορείς εύκολα να εντοπίσεις κάθε αλλαγή και να αναιρέσεις οτιδήποτε δεν σου αρέσει.

--- /task ---

--- task ---

**Εντοπισμός σφαλμάτων:**

Εάν προσθέσεις κώδικα σε λάθος αντικείμενο, μπορείς να το διορθώσεις:

[[[scratch3-copy-code]]]

Εάν χρειαστεί, μπορείς να επαναφέρεις τα εφέ γραφικών:

--- collapse ---
---
title: Δε θέλω αυτά τα γραφικά εφέ
---

Για να επαναφέρεις τα γραφικά εφέ ανά πάσα στιγμή, κάνε κλικ στο μπλοκ`επανάφερε εφέ γραφικών`{:class="block3looks"} στο `Όψεις`{:class="block3looks"}. Κάνοντας κλικ στην πράσινη σημαία διαγράφονται επίσης τα εφέ γραφικών.

```blocks3
clear graphic effects
```
--- /collapse ---

--- /task ---

--- task ---

**Δοκιμή:** Δοκίμασε ξανά το έργο σου, αλλά αυτή τη φορά, κάνε το σε πλήρη οθόνη, ώστε να μπορείς να δεις πώς θα φαίνεται σε κάποιον που το κοιτάζει.

[[[scratch3-full-screen]]]

--- /task ---

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Κάνοντας το έργο σου σε πλήρη οθόνη, βλέπεις τι έχεις κάνει από την πλευρά ενός χρήστη που παίζει με το έργο σου. **Η αλληλεπίδραση χρήστη** είναι σημαντική στην ψηφιακή δημιουργία. 
</p>


