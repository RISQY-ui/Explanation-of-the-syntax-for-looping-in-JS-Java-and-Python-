

---

📁 1. Java – Perulangan for

```java
public class Perulangan {
    public static void main(String[] args) {
        // Perulangan dari 0 sampai 4 (5 kali)
        for (int i = 0; i < 5; i++) {
            System.out.println("Java perulangan ke-" + i);
        }
    }
}
```

Penjelasan bahasa Indonesia:

· int i = 0 → mulai dari angka 0
· i < 5 → ulangi selama i masih kurang dari 5
· i++ → setelah satu putaran, i bertambah 1
· Maka akan tampil: 0, 1, 2, 3, 4

---

🐍 2. Python – Perulangan for

```python
# Perulangan dari 0 sampai 4 (5 kali)
for i in range(5):
    print(f"Python perulangan ke-{i}")
```

Penjelasan bahasa Indonesia:

· range(5) → menghasilkan urutan angka 0, 1, 2, 3, 4
· i akan mengambil satu per satu angka dari range tersebut
· Tidak perlu i++ karena Python sudah mengatur otomatis
· Maka akan tampil: 0, 1, 2, 3, 4

---

🌐 3. JavaScript – Perulangan for

```javascript
// Perulangan dari 0 sampai 4 (5 kali)
for (let i = 0; i < 5; i++) {
    console.log(`JavaScript perulangan ke-${i}`);
}
```

Penjelasan bahasa Indonesia:

· let i = 0 → mulai dari angka 0
· i < 5 → ulangi selama i masih kurang dari 5
· i++ → setelah satu putaran, i bertambah 1
· Maka akan tampil: 0, 1, 2, 3, 4

---

📊 Perbandingan Cepat (Bahasa Indonesia)

Bahasa Cara nulis perulangan Penjelasan singkat
Java for (int i = 0; i < 5; i++) Tulis tipe data + manual tambah 1
Python for i in range(5): Paling simpel, range otomatis
JavaScript for (let i = 0; i < 5; i++) Mirip Java, tanpa tipe data int

---

