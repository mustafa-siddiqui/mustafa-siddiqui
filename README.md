### Hi, I'm Mustafa 👋🏼

![headerImage](https://github.com/mustafa-siddiqui/mustafa-siddiqui/blob/master/headerImage.png)

```yaml
jobs:
  publish:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@master
        with:
          persist-credentials: false
          fetch-depth: 0
      - name: Create README.md
        uses: actions-js/profile-readme@master
        with:
          username: <your username>
          github_token: ${{ secrets.GITHUB_TOKEN }}
      - name: Commit & Push changes
        uses: actions-js/push@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```

<!--GITHUB_ACTIVITY:{"rows": 5}-->

---

<p align="center">
  Last refresh: 
  <b><!--TIMESTAMP--></b>
</p>

I am currently a junior international student at the University of Rochester. I am pursuing my undergraduate degree in electrical and computer engineering. Recently, I've started exploring the world of embedded systems and am fascinated by it. The intersection of hardware and software intrigues me. With a deep love of solving problems and building stuff, I hope to contribute to the world in a meaningful way.

While I am not working, I love to explore new places, hang out with friends, and read - fiction & poetry. I also love to play soccer & chess.

Connect with me on [LinkedIn](https://www.linkedin.com/in/-mustafasiddiqui/)!
