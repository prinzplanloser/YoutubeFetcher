Создано приложение для анализа каналов на Youtube.
Созданы структуры хранения информации о канале и видео канала в mongoDB, описаны в виде JSON с указанием типов полей. 
Созданы необходимые модели для добавления и удаления данных из коллекций.
  Реализован класс статистики, который может возвращать:
  - Суммарное кол-во лайков и дизлайков для канала по всем его видео
  - Топ N каналов с лучшим соотношением кол-во лайков/кол-во дизлайков
