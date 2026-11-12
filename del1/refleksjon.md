# Refleksjon: Grunnleggende JavaScript

Svar når du er ferdig med oppgavene i `oppg1_grunnleggende.js`. Skriv med egne ord, og ikke se i koden mens du svarer på del A. Korte svar er helt greit.

---

## A. Forklar med egne ord

**1. Hva er forskjellen på `let` og `const`? Når bruker du hvilken?**

> let kan reasignes, const er konstant og kan derfor ikke reasignes

**2. Hvorfor ble `"5" + 5` til `55`, mens `5 + 5` ble `10`?**

> "5" er en string, som vil si at den ikke har en verdi og koden leser den som vanlig tekst, mens 5 + 5 er to verdie som legges sammen, blir "5" + 5 mer som tekst + 5 som blir tekst5

**3. Hva gjør `%`? Gi et eksempel fra oppgavene der du brukte den.**

> % vil att alle verdiene som blir når man deler med den skal være hele. derfor blir det rest. for eksempel 3%2 blir 1 til rest. siden 1.5 ikke er hele tall

**4. Hva er forskjellen på `=` og `===`?**

> = bestemme hva noe skal være. === sjekker hva noe er

**5. Forklar de tre delene i denne linja:** `for (let i = 1; i <= 5; i++)`

> "let i = 1", setter i til 1. "i<=5", sjekker att i er mindre eller lik 5, "i++", legger tli 1 til i hver gang.

**6. Når er en `while`-løkke bedre enn en `for`-løkke? Hva kan gå galt med en `while`-løkke?**

> hvis noe skal skje mens noe er sant eller ikke

**7. Hvorfor er den første byen i lista `byer[0]` og ikke `byer[1]`?**

> fordi arrays starter på 0, aløtså første elemtn i en array er 0

---

## B. Bruk det du har lært

**8. Hva skrives ut her? Svar før du tester.**

```js
const temp = -3;
if (temp < -5) {
  console.log("Veldig kaldt");
} else if (temp < 0) {
  console.log("Kaldt");
} else {
  console.log("Mildt");
}
```

> kaldt

**9. Hva skrives ut her? Svar før du tester.**

```js
const lag = ["Titans", "Ulvene", "Polarnatt"];
lag.push("Nordlys");
console.log(lag.length);
console.log(lag[1]);
```

> Ulvene

**10. Denne koden skal skrive ut 1, 2 og 3, men gjør det ikke. Hva er feil?**

```js
for (let i = 1; i < 3; i++) {
  console.log(i);
}
```

> "i < 3", btyr at det bare gjentar mens "i" er mindre en 3. altså bare 2 gangeri dette tillfellet, hvis an heller bruker "i <=3" vil koden skrive 1 2 3

---

## C. Om din egen læring

**11. Hvilken oppgave var vanskeligst, og hvordan løste du den?**

> oppgave 23. jeg hadde skrevet "lengt" istedet for "length"

**12. Hvilken feilmelding fikk du oftest? Hva betydde den?**

> jeg fikk ikke noen feilmeldinger som vi ikke var ment å få

**13. Hva gjorde du når du sto fast? Hva vil du gjøre annerledes neste gang?**

> jeg søkte på nett for å lese om hvordan ting fungerer. jeg trr jeg ville gjort det samme neste gang, eller brukt AI for å forklare hvis det er vanskeligere

**14. Hvor langt kom du?**

| Nivå | Kryss av |
|---|---|
| Grunnleggende | x |
| Middels | x |
| Avansert | x |

**15. Kryss av for det du kan nå.**

| Jeg kan... | Ja | Litt | Nei |
|---|---|---|---|
| lage variabler med `let` og `const` | x |  |  |
| bruke tekst og tall, og sette dem sammen med `${}` |  | x |  |
| ta valg med `if`, `else if` og `else` | x |  |  |
| skrive en `for`-løkke | x |  |  |
| hente, legge til og gå gjennom verdier i en array |  | x |  |
| lese en feilmelding og finne riktig linje | x |  |  |

**16. Hva vil du øve mer på før vi går videre til funksjoner?**

> arrays