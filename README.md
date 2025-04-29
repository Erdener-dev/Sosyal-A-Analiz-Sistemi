# Sosyal Ağ Analiz Sistemi

Bu proje, C dili ile geliştirilmiş bir sosyal ağ analiz sistemidir.  
Amaç, kullanıcılar arası ilişkileri grafik yapısıyla temsil edip, analiz işlemlerini ağaç tabanlı veri yapıları üzerinden gerçekleştirmektir.

## Özellikler

- Kullanıcılar Red-Black Tree yapısı ile tutulur.
- Kullanıcılar arasında arkadaşlık ilişkileri bağlı liste ile temsil edilir.
- Derinlik öncelikli arama (DFS) ile belirli mesafedeki arkadaşlar bulunur.
- İki kullanıcı arasında ortak arkadaşlar tespit edilir.
- Ağ içerisindeki topluluklar (connected components) belirlenir.
- Her bir kullanıcının etki alanı hesaplanır.

## Kullanılan Veri Yapıları

- Red-Black Tree: Kullanıcıları ID'ye göre hızlı eklemek ve aramak için.
- Linked List: Kullanıcıların arkadaş listelerini tutmak için.
- DFS algoritması: Ağ üzerinde dolaşmak ve analizler yapmak için.

## Derleme ve Çalıştırma

Linux veya GCC uyumlu ortamda:

