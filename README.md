#Step by Step Setting DNS on Niagahoster and Deployment Vercel

1. Register/Login Niagahoster Account

   ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.29.50.jpeg "daftar/login niagahoster")

2. Get a New Domain and complete the payment
   ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.30.34.jpeg "cari domain baru dan selesaikan pembayaran")

3. Manage domain to setting DNS
   ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.31.25.jpeg "manage domain")

4. Set configuration DNS from vercel

- Set CNAME configuration
  ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.32.04.jpeg "setting dns custom")

  ***

- Set A configuration
  ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.32.17.jpeg "Shiprock, New Mexico by Beau Rogers")
  > **DNS Configuration by vercell**
  >
  > 1. CNAME
  >    > - Type: A
  >    > - Name: www
  >    > - Content: cname-vercel-dns.com
  >    > - TTL: 14400

> 2. A Configuration
>    > - Type: A
>    > - Name: @
>    > - Content: 76.76.21.21
>    > - TTL: 100

5. After validation and successfully connected to niagahoster DNS, the domain can be used!
   ![An old rock in the desert](./assets/Readmenih/WhatsApp%20Image%202023-11-14%20at%2002.32.52.jpeg "dns berhasil diubah")

## Thanks for enjoy the content!

### Muhammad Rizki Aldiansyah
