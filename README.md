Пропатченное ядро 4.9.158 для ejudge cm. https://ejudge.ru/wiki/index.php/%D0%9F%D0%B0%D1%82%D1%87_%D0%BA_%D1%8F%D0%B4%D1%80%D1%83_Linux.
Для установки ядра нужно выполнить:
dpkg -i linux-headers-4.9.158-cher1-vanilla_1.0.ejudge_amd64.deb
dpkg -i linux-image-4.9.158-cher1-vanilla_1.0.ejudge_amd64.deb

(чисто теоретички ещё надо сделать update-grub, но на aws всё заработало без этого)


CheckPatch - проверяет установлен ли патч. 0 - установлен, -1 - не установлен. Можно вызвать с аргументом text, тогда будет напечатано установлен или нет.
