mishabetmen — Android
=====================

Исходники для сборки APK (buildozer):
  main.py / app_android.py
  security.py
  license_keys.py
  buildozer.spec

Сборка (WSL/Linux):
  pip install buildozer cython
  buildozer android debug

APK: bin/*.apk

В приложении только ввод ключа (из админки на ПК).
Генерации ключа на телефоне нет.
