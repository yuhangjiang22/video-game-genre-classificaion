# Video Game Genre Classification
## Abstract
Video games have played a more and more important role in our life. While the genre classification is a deeply explored research subject by leveraging the strength of deep learning, the automatic video game genre classification has drawn little attention in academia. In this study, we compiled a large dataset of 50,000 video games, consisting of the video game covers, game descriptions and the genre information. We explored three approaches for genre classification using deep learning techniques. First, we developed five image-based models utilizing  pre-trained computer vision models such as MobileNet, ResNet50 and Inception, based on the game covers. Second, we developed two text-based models, using Long-short Term Memory(LSTM) model and the Universal Sentence Encoder model, based on the game descriptions. For the third approach, we constructed a multi-modal fusion model, which concatenates extracted features from one image-based model and one text-based model. We analysed our results and revealed some challenges that exist in the task of genre classification for video games. Some future works are also proposed.
## Dataset
We compiled a dataset of 50,000 video games in 21 different game genres including information about title text, the game cover image, descriptive text, and the associated genres, collected from [IGDB](http://igdb.com), a video game database intended for both game consumers and video game professionals alike.

|   |   |   |   |   |   |   |
|---|---|---|---|---|---|---|
|Hack and slash/Beat’em up|Adventure   |Arcade   | Fighting  |Indie   |Music|Pinball|
|  Platform |   Point and click | Puzzle  | Quiz/Trivia|Racing  | Racing  |Racing|Real Time Strategy(RTS)|Role-playing(RPG)|
|   Shooter|  Simulator | Sport  | Strategy  | Tactical  |Turn-basedstrategy(TBS)|VisualNovel|
