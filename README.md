# TestRepo
Test Repo!

# Breakfast
For breakfast I had toast with a cup of tea.

[This is a link to my LinkedIn!](https://www.linkedin.com/in/emily-perry-a72324223/)  
![Hello Octocat!](https://octodex.github.com/images/boxertocat_octodex.jpg)

## Favourite Games
1. Pokemon Pearl
2. Pokemon Mystery Dungeon Blue
3. Splatoon 2
4. The Legend of Zelda: Majora's Mask
5. Danganronpa

## Pro Dev Checklist

- [x] Research report topic
- [ ] Write report
- [ ] Code portfolio

```void saveScores(vector<ScoreEntry>& scores)
{
    ofstream outFile;
    outFile.open("scores.txt", ios::trunc);
    for (int i = 0; i < scores.size(); i++)
    {
        outFile << scores[i].name << endl << scores[i].score;
        if (i < scores.size() - 1)
        {
            outFile << endl;
        }
    }
    outFile.close();
}
```

:cat2: :video_game:
