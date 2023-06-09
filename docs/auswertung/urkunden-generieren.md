---
sidebar_position: 1
---

import ReactPlayer from "react-player";

# Urkunden generieren

<div className="video__wrapper">
  <ReactPlayer
    className="video__player"
    controls
    config={{
      file: {
        attributes: {
          poster:
            "https://storage.googleapis.com/files.bujus.de/school-app-tutorials/school-app-urkunden-generieren-tutorial-thumbnail.jpg",
        },
      },
    }}
    height="100%"
    url="https://storage.googleapis.com/files.bujus.de/school-app-tutorials/school-app-urkunden-generieren-tutorial.mp4"
    width="100%"
  />
</div>

## Einleitung

Wenn alle Ergebnisse eingetragen sind, können Sie die Urkunden generieren.

Manchmal kann für einige Teilnehmer keine Urkunde generiert werden. Dies liegt dann daran, dass diesen Teilnehmern noch Ergebnisse fehlen, ohne die keine Auswertung stattfinden kann.

## Urkunden generieren

1. Navigieren Sie zur `Urkunden-Übersicht`.
2. Klicken Sie oben rechts auf `Generieren`. Es öffnet sich ein Dialog.
3. Klicken Sie auf `Generieren`.

<!-- :::tip

**Wieso aktualisieren sich die Urkunden nicht, wenn ich Ergebnisse ändere?**

Wenn Sie die Ergebnisse ändern, werden die Urkunden nicht automatisch aktualisiert. Sie müssen die Urkunden immer erneut generieren.

::: -->

## Nicht generierbare Urkunden ansehen

1. Navigieren Sie zur `Urkunden-Übersicht`.
2. Klicken Sie oben rechts auf `Generieren`. Es öffnet sich ein Dialog.
3. Klicken Sie auf `Generieren`.
4. Klicken Sie oben rechts auf den Tab `Nicht generierte Urkunden`. Dort sehen Sie, welche Urkunden nicht generiert werden konnten und welche Ergebnisse für diese schon erbracht wurden und welche noch fehlen.

## Nicht generierte Urkunden beheben

Um nicht generierte Urkunden zu beheben, müssen Sie die fehlenden Ergebnisse nachtragen und die Urkunden dann erneut generieren.
