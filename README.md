# IPC-distributed-system
# Projekt IPC Server & Klient

Ky projekt implementon një server dhe klient për komunikim nëpërmjet mekanizmave të komunikimit IPC (Inter-Process Communication) në Ubuntu. Serveri është në gjendje të pranojë kërkesa nga klientët e shumtë njëkohësisht duke përdorur mekanizma te IPC , threads dhe sinkronizim. Klientët mund të lidhen me serverin, të dërgojnë kërkesa dhe të marrin përgjigjen e kërkesës së tyre.

## Specifikimet e Projektit

1. Implementimi duhet të përfshijë një program serveri që mund të pranojë kërkesa nga klientët duke përdorur mekanizmat e IPC, threads dhe sinkronizim.
2. Programi server duhet të jetë në gjendje të pranojë një numër maksimal të klientëve, ku numri maksimal përcaktohet në një konstante ose file konfigurimi.
3. Klientët duhet të jenë në gjendje të lidhen me serverin dhe të dërgojnë kërkesa duke përdorur mekanizmat e IPC.
4. Serveri duhet të kthejë prapa të dhënat e kërkesës së klientit në përgjigjen e serverit.
5. Implementimi duhet të tregojë përdorimin e duhur të mekanizmave të sinkronizimit për të siguruar ndarjen dhe mbrojtjen e burimeve.
6. Implementimi duhet të jetë i dokumentuar mirë dhe i lehtë për tu kuptuar.

## Struktura e Projektit

- `server.c`: Kod i serverit që pranon dhe përpunon kërkesat nga klientët.
- `client.c`: Kod i klientit që lidhet me serverin dhe dërgon kërkesa.

## Komplajimi dhe Ekzekutimi

1. Komplajto serverin dhe klientin duke përdorur komandën:

    ```
    gcc -o server server.c -pthread 
    gcc -o client client.c 
    ```

2. Ekzekuto serverin duke shkruar në terminal:

    ```
    ./server
    ```

3. Ekzekuto klientin duke shkruar në terminal:

    ```
    ./client
    ```

4. Në terminalin e klientit, shkruani kërkesat tuaja dhe shihni përgjigjen nga serveri.

## Shembulli i Përdorimit

1. Ekzekuto serverin në një terminal.

2. Ekzekuto klientin në një terminal tjetër.

3. Në terminalin e klientit, shkruani një kërkesë dhe pritni përgjigjen nga serveri.

4. Përsëriteni hapin 3 për kërkesa të tjera.

5. Për të mbyllur klientin, shkruani "exit".

6. Për të mbyllur serverin, ndërpritni ekzekutimin e programit.



## Autorët

- Alketa Bala
- Maltine Rama 
- Jetlira Hoxha 
- Ylleza Luma

© 2023 

