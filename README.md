# GKI KernelSU-Next для CMF Phone 1 (tetris)

Автосборка GKI-ядра `common-android14-6.1` (KMI `android14-11`) с KernelSU-Next
через GitHub Actions. Запуск: вкладка **Actions → выбрать workflow → Run workflow**.
Артефакт `GKI-KernelSUNext-tetris` появится на странице завершённого run.

Wi-Fi/BT/звук не ломаются: `CFG80211/MAC80211/BT/SND/IKHEADERS/BPF_LSM` не трогаем
(в GKI они модули из system_dlkm), protected exports удалены.
