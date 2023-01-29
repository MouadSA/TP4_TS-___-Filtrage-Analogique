# TP4_TS-___-Filtrage-Analogique
1)Définir le signal x(t)

![image](https://user-images.githubusercontent.com/79712514/215358795-e94900e3-60f6-4410-8cdf-beb8621d2446.png)

2)Tracer le signal x(t) avec sa transforme de Fourier

![image](https://user-images.githubusercontent.com/79712514/215358824-2bd59414-a109-495f-a488-c95ef7e62458.png)

on remarque que le premier signal n'est pas précis

![image](https://user-images.githubusercontent.com/79712514/215358889-849c864d-3b1b-40dc-8136-d353a230d83f.png)

![image](https://user-images.githubusercontent.com/79712514/215358899-5e40b794-8e85-4cbd-aaf4-0f258b199c62.png)

on sait que H(f) = (K.j.w/wc) / (1 + j. w/wc)

1)Tracer le module de la fonction H(f)

![image](https://user-images.githubusercontent.com/79712514/215358949-7344b72a-4600-4387-bbed-7dbb3a669cea.png)

![image](https://user-images.githubusercontent.com/79712514/215358963-6d11238c-53fe-4317-b3ce-f0c878146755.png)

2)Tracer 20.log(|H(f)|) pour différentes pulsations de coupure wc

![image](https://user-images.githubusercontent.com/79712514/215358981-091b5eed-6ba7-41ca-b7d7-09ad75e5bf6e.png)

![image](https://user-images.githubusercontent.com/79712514/215358994-9923b7ac-0996-4fdd-80aa-3b7fffa54de6.png)

3)on choisit différentes fréquences de coupure

![image](https://user-images.githubusercontent.com/79712514/215359009-5bee3172-75b7-46dd-a62b-fed48ea067be.png)

![image](https://user-images.githubusercontent.com/79712514/215359015-dcd333d1-e69f-4fc1-84dd-9521a9cbe3d8.png)

4)Choix de wc optimal

En appliquant la transmittance complexe de fréquence 500 sur le signal, on peut remarquer une réduction de l'amplitude du signal sur toute sa longueur, avec une réduction plus importante dans les fréquences basses. 

5)on observe le signal y(t)

![image](https://user-images.githubusercontent.com/79712514/215359072-5f6fc82e-3b5c-48bd-bd1f-97e323dd2aff.png)

Dé-bruitage d'un signal sonore filtrage

2) Mettez-la en oeuvre

![image](https://user-images.githubusercontent.com/79712514/215359114-4aee8ec3-c958-43f5-86fd-e5333ad8f2b8.png)

![image](https://user-images.githubusercontent.com/79712514/215359122-6aecd9b1-fc5e-4b18-a9b6-110126dc7ae1.png)

3-un filtre analogique ne permet que de réduire le bruit, et comme nous l'avons vu auparavant, lors de la réduction du bruit dans un autre signal, il n'est pas possible de filtrer le signal avec une transmittance complexe d'ordre 1 sans affecter le signal. Par conséquent, un filtre passe-bas de premier ordre ne sera pas efficace pour éliminer le bruit.

4) on ameliore la qualite en augmentant l'ordre

![image](https://user-images.githubusercontent.com/79712514/215359156-240110fa-78d2-4a53-b00f-c71aebd7757b.png)


