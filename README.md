# Real-time-seismic-wave-plot-with-amplitude-alert
Acest cod va ajuta sa vizualizati forma de unda seismica rezultata din pachetele de date MiniSeed apropae de timpul real si va permite sa setati o alerta sonora atunci cand pragul amplitudinii setate este depasit 

En

This code will help you visualize the seismic waveform resulting from the MiniSeed data packets close to real time and will allow you to set a sound alert when the threshold of the set amplitude is exceeded (in the code the target amplitude for triggering the sound signal was set to 6000) . Replace the server used for testing with your server address for optimal results. To use this code, it is necessary to install Python 3.8.10 or higher and the program is initialized using the command python3 seismograph.py or python seismograph.py depending on the existing Python version on your computer. The amplitude of the signal is automatic and changes automatically depending on the amplitude of the packets received from the server through the "ax.autoscale_view()" code sequence. To manually change the amplitude on the Plot, add below the following code sequence: "x.set_ylim(-20, 20)"

Ro

Acest cod va ajuta sa vizualizati forma de unda seismica rezultata din pachetele de date MiniSeed apropae de timpul real si va permite sa setati o alerta sonora atunci cand pragul amplitudinii setate este depasit (in cod amplitudinea tinta pentru declansarea semnalului sonor a fost setata la 6000). Inlocuiti server-ul utilizat pentru testare cu adresa serverului dumneavoastra pentru rezultate optime. Pentru utilizarea acestui cod este necesara instalarea Pyhton 3.8.10 sau mai mare iar programul se initializeaza folosind comanda python3 seismograph.py sau python seismograph.py in functie de versiunea Python existenta pe calculatorul dumneavoastra. Amplitudinea semnalului este automata si se automodifica in functie de amplitudinea pachetelor primite de la server prin secventa de cod "ax.autoscale_view()". Pentru a modifica manual amplitudinea pe Plot adaugati dedesubt secventa de cod urmatoare: "x.set_ylim(-20, 20)"
<img src="https://i.ibb.co/ZNYM1M7/Screenshot-from-2023-03-09-17-52-13.png"></img>
