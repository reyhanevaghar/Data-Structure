def BFS(graph , start):
    queue = [start]
    visited = {start}
    while queue:
        vertex = queue.pop(0)
        for ne in graph[vertex]:
            visited.add(ne)
            queue.append(ne)
    return visited
def DFS(graph , start , visited):
    visited[start] = True
    for ne in graph[start]:
        if not visited[ne]:
            DFS(graph , ne , visited)
