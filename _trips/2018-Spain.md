---
trip: camino2018
name: Camino de Santiago, Spain 2018
---

# On the Camino de Santiago de Compostela

The *Camino* is a pilgrimage route across Spain. We flew from Vancouver to Biarritz, France via London Gatwick on WestJet followed by easyJet, then to Bayonne where we spent two nights to adjust for the time zone. While there, we made a side day-trip to San Sebastian, Spain.

From Bayonne, it was a short train ride to St-Jean-Pied-de-Port, France, where we started our walk along the *Camino Frances*.

We used John Brierly's [*A Pilgrim's Guide to the Camino de Santiago: St. Jean - Roncesvalles - Santiago*](https://www.goodreads.com/book/show/30316184-a-pilgrim-s-guide-to-the-camino-de-santiago), which was very insightful and I would highly recommend it.

While on the *Camino*, I kept journals of the trip which have been uploaded online here, with some minor grammatical changes (to be fair, I was typing everything out on my old iPhone 6 at the time) and some *Editor's Notes* that I've added post-trip. I've also included some photos, but I also didn't have a very good camera at the time (either the Xiaomi Mi 6 phone or my iPhone 6).

<ul>
    {% for post in site.posts reversed %}
        {% if post.trip == 'camino2018' %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>
