### Hi there 👋


## Bio🧑🏻
```csharp
> Console.WriteLine("Years of experiences: " + (int)itJourneyStart.TotalYears);
Years of experiences: 3
```

### **ToolsAndLanguages.cs**
```csharp
30  using (SKSurface surface = SKSurface.Create(new SKImageInfo(toolsAndLanguages.Count * (imageSize + 10), 60)) {
31    SKCanvas canvas = SKSurface.Canvas;
32    canvas.Clear(SKColors.Transparent);
33
34    for (int i = 0; i < toolsAndLanguages.Count; i++) {
35      SKBitmap icon = toolsAndLanguages[i].Resize(new SKImageInfo(imageSize, imageSize), SKFilterQuality.High);
36      canvas.DrawBitmap(icon, (imageSize + 10) * i, (60 - imageSize) / 2);
37    }
38
39    using (SKImage image = surface.Snapshot())
40    using (SKData output = image.Encode(SKEncodedImageFormat.Png, 100))
41      RenderImage(output.ToArray());
42  }
```

<img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-line.svg" title="C#" alt="C#" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/go/go-original-wordmark.svg" title="Go" alt="Go" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain-wordmark.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-plain-wordmark.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/sqlite/sqlite-original-wordmark.svg" title="SQLite" alt="SQLite" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original-wordmark.svg" title="VS Code" alt="VS Code" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/nginx/nginx-original.svg" title="Nginx" alt="Nginx" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/fedora/fedora-plain.svg" title="Fedora" alt="Fedora" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;

---

## Stats

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TheLanc3&layout=compact&theme=vision-friendly-dark)](https://github.com/TheLanc3)

[![TheLanc3's Github Stats](https://github-readme-stats.vercel.app/api?username=TheLanc3&show_icons=true&layout=compact&theme=dark)](https://github.com/TheLanc3)
