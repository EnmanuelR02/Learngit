# Analisis-de-Sistema
### Juego de Lear Git Branching

---

## Comandos...

<ul>
    <li>Git Commit</li>
        <p>Ejemplo: git commit en una rama cualquiera.</p>
        <br>
    <li>Git branch</li>
        <p>git branch bugFix</p>
        <br>
    <li>Git merge</li>
        <ol>
            <li>git checkout -b bugFix</li>
            <li>git checkout main</li>
            <li>git commit</li>
            <li>git checkout main</li>
            <li>git commit</li>
            <li>git merge bugFix</li>
        </ol>
        <br>
    <li>Git rebase</li>
        <ol>
            <li>git checkout -b bugFix</li>
            <li>git commit</li>
            <li>git checkout main</li>
            <li>git commit</li>
            <li>git checkout bugFix</li>
            <li>git rebase main</li>
        </ol>
        <br>
    <li>Git HEAD</li>
        <p>git checkout c4</p>
        <br>
    <li>Git reverse</li>
        <ol>
            <li>git reset local~1</li>
            <li>git checkout pushed</li>
            <li>git revert pushed^1</li>
        </ol>
        <br>
    <li>Git cherry-pick</li>
        <p>git cherry-pick c3 c4 c7</p>
        <br>
    <li>Git tags</li>
        <ol>
            <li>git tag v0 c1</li>
            <li>git tag v1 c2</li>
            <li>git checkout c2</li>
        </ol>
        <br>
    <li>Git describe</li>
    <p>git commit</p>
    <br>
</ul>

---

### Fotos de juego completado:
   + ![Git learn game](/img/1.jpg)
   + ![Git learn game](/img/2.jpg)

### Creador:
   + #### Limberth Romero. 2022/0278
