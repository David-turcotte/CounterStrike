# CounterStrike
Additionne les nombres jusqu'à celui est afficher

Doit mettre ses 3 fichiers dans l'ordre: jquerywaypoints, jquerycouterup et counterstrike


$('.counter').counterUp({
    delay: 10,
    time: 1000,
    offset: 70,
    beginAt: 100,
    formatter: function (n) {
      return n.replace(/,/g, '.');
    }
});
