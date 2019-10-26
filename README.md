Diese Hoodfile kann nur verwendet werden, wenn der Public Key des Routers in list.key eingetragen ist. Für jeden Key ist eine neue Zeile zu verwenden.

Key können folgendermaßen aus dem Router ausgelesen werden:

echo "secret \"$(uci get fastd.fff.secret)\";" > /tmp/sec && fastd --show-key -c /tmp/sec

Pull Requests werden nur nach persönlichen Kontakt und auf Anfrage akzeptiert
