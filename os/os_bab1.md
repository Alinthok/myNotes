# BAB 1

## Operating System

Operating System (Sistem Operasi) adalah part dari sistem komputer yang tujuannya untuk mengontrol cara hardware bekerja dan menampilkannya ke user.

## Key Aspect Of Operating System

### Interrupts

Interrupt adalah fitur dari CPU yang bisa menyetop apa saya yang dilakukan oleh CPU sekarang untuk menjalankan suatu kode/process dan melanjutkan kerja CPU ke progam yang distop tadi. Interrupt ini biasanya digunakan untuk Timer dan I/O devices.

### Storage Structure

Storage structure di sebuah sistem komputer biasanya terdiri dari:  

- Non-volatile memory.
- Volatile memory.

Non-volatile memory adalah storage device yang datanya tidak hilang ketika komputer dimatikan. Sedangkan Volatile memory adalah storage device yang datanya hilang ketika komputer dimatikan. Volatile memory lebih cepat dari non-volatile memory tetapi harga per bitnya lebih mahal.

#### General Storage Structure

Pada sistem komputer yang biasanya program komputer yang sedang di jalankan ditaruh di volatile memory dan program yang disimpan berupa file ditaruh di non-volatile memory dan komputer mempunyai memory khusus untuk menyimpan bootstrap program (program untuk menjalankan OS) yang dinamakan EEPROM.

### I/O Structure

Komputer juga harus bisa berinteraksi dengan I/O device. I/O device berinteraksi dengan komputer dapat menggunakan:

- Interrupt based I/O.
- Menggunakan DMA (direct memory access). I/O device bisa mengirim data langsung ke memory.

## Common OS Operations

### Multiprogramming and Multitasking


