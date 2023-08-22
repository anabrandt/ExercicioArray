<!DOCTYPE html>
<html>
<head>
    <title>Lista de Tarefas</title>
</head>
<body>

<h1>Lista de Tarefas</h1>

<form id="task-form">
    <label for="task">Nova Tarefa:</label>
        <input type="text" id="task" required placeholder="Digite sua tarefa">
        <button type="submit">Adicionar Tarefa</button>
    </form>
</form>

<form id="task-form">
    <label for="task">Nova Tarefa:</label>
    <input type="text" id="task" required placeholder="Digite sua tarefa">
    <label for="priority">Prioridade:</label>
    <select id="priority">
    </select>
    <label for="type">Tipo:</label>
    <select id="type">
    </select>
    <button type="submit">Adicionar Tarefa</button>
</form>

<ul id="task-list">
</ul>

<script src="./js/script.js"></script>
</body>
</html>
