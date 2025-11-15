# Tempo and Genre

The style (or genre) of a piece of music is determined by a number of factors, including the types of sounds and patterns used, and also the tempo.

You probably have some idea about the genre of a song when you hear it, just based on your experiences as a music listener. Here are "typical" tempo ranges for a number of common genres:

- Dub: 60-90 bpm
- Hip-hop: 60-100 bpm
- House: 115-130 bpm
- Techno/trance: 120-140 bpm
- Dubstep: 135-145 bpm
- Drum and bass: 160-180 bpm

[https://strudel.cc/#c2V0Y3BtKDE2Mi80KQoKJG9wZW5IYXQ6IHMoIlt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gb2ggfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbG9zZWRIYXQ6IHMoIlt%2BIH4gaGggfl1bfiB%2BIGhoIH5dW34gfiBoaCB%2BXVt%2BIH4gfiBoaF0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbGFwOiBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikKJGtpY2s6IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiB%2BIH5dW34gfiB%2BIH5dIikuYmFuaygiUm9sYW5kVFI5MDkiKQ%3D%3D](https://strudel.cc/#c2V0Y3BtKDE2Mi80KQoKJG9wZW5IYXQ6IHMoIlt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gfiB%2BXVt%2BIH4gb2ggfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbG9zZWRIYXQ6IHMoIlt%2BIH4gaGggfl1bfiB%2BIGhoIH5dW34gfiBoaCB%2BXVt%2BIH4gfiBoaF0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpCiRjbGFwOiBzKCJbfiB%2BIH4gfl1bY3AgfiB%2BIH5dW34gfiB%2BIH5dW2NwIH4gfiB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikKJGtpY2s6IHMoIltiZCB%2BIH4gfl1bfiB%2BIH4gYmRdW34gfiB%2BIH5dW34gfiB%2BIH5dIikuYmFuaygiUm9sYW5kVFI5MDkiKQ%3D%3D)

Try adjusting the tempo (change from `162` to `60` for example) while this beat plays and listen to how it changes character, even if the pattern stays exactly the same.

## Strudel Notation: Fast & Slider

If you recall on the Strudel Workshop Recap,

https://strudel.cc/workshop/recap/

We can use `.fast(multiplier)` to also speed up our track.

We can also use `slider(default, min, max, step)` to display a nice slider interface.

In this example, we are going to use a slider to adjust the speed.

[https://strudel.cc/#c2V0Y3BtKDUwLzQpCgpsZXQgZmFzdE11bHRpcGxpZXIgPSBzbGlkZXIoMi40LCAxLCA0LCAwLjEpCgokb3BlbkhhdDogcygiW34gfiB%2BIH5dW34gfiB%2BIH5dW34gfiB%2BIH5dW34gfiBvaCB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikuZmFzdChmYXN0TXVsdGlwbGllcikKJGNsb3NlZEhhdDogcygiW34gfiBoaCB%2BXVt%2BIH4gaGggfl1bfiB%2BIGhoIH5dW34gfiB%2BIGhoXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikuZmFzdChmYXN0TXVsdGlwbGllcikKJGNsYXA6IHMoIlt%2BIH4gfiB%2BXVtjcCB%2BIH4gfl1bfiB%2BIH4gfl1bY3AgfiB%2BIH5dIikuYmFuaygiUm9sYW5kVFI5MDkiKS5mYXN0KGZhc3RNdWx0aXBsaWVyKQoka2ljazogcygiW2JkIH4gfiB%2BXVt%2BIH4gfiBiZF1bfiB%2BIH4gfl1bfiB%2BIH4gfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpLmZhc3QoZmFzdE11bHRpcGxpZXIp](https://strudel.cc/#c2V0Y3BtKDUwLzQpCgpsZXQgZmFzdE11bHRpcGxpZXIgPSBzbGlkZXIoMi40LCAxLCA0LCAwLjEpCgokb3BlbkhhdDogcygiW34gfiB%2BIH5dW34gfiB%2BIH5dW34gfiB%2BIH5dW34gfiBvaCB%2BXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikuZmFzdChmYXN0TXVsdGlwbGllcikKJGNsb3NlZEhhdDogcygiW34gfiBoaCB%2BXVt%2BIH4gaGggfl1bfiB%2BIGhoIH5dW34gfiB%2BIGhoXSIpLmJhbmsoIlJvbGFuZFRSOTA5IikuZmFzdChmYXN0TXVsdGlwbGllcikKJGNsYXA6IHMoIlt%2BIH4gfiB%2BXVtjcCB%2BIH4gfl1bfiB%2BIH4gfl1bY3AgfiB%2BIH5dIikuYmFuaygiUm9sYW5kVFI5MDkiKS5mYXN0KGZhc3RNdWx0aXBsaWVyKQoka2ljazogcygiW2JkIH4gfiB%2BXVt%2BIH4gfiBiZF1bfiB%2BIH4gfl1bfiB%2BIH4gfl0iKS5iYW5rKCJSb2xhbmRUUjkwOSIpLmZhc3QoZmFzdE11bHRpcGxpZXIp)

# Next: Backbeats

[Backbeats](Backbeats%202ac98431b24181779622d572bfaead4c.md)

---

Previous:

[Beat and Tempo](Beat%20and%20Tempo%202ac98431b24181c091e8c66c8662fa75.md)