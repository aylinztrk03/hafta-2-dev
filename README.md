import math
points = [(1, 2), (3, 4), (5, 6), (7, 8), (9, 10)]
def euclidean_dictance(point1, point2):
    return math.sqrt((point2[0] - point1[0])**2 + (point2[1] - point2[1])**2)

distance = []
for i in range(len(points)):
    for j in range(i + 1, len(points)):
        distance = euclidean_distance(points[i], points[j])
        distances.append(distance)

min_distance = min(distances)
print(f"Minimum mesafe: {min_distance}")


Minimum mesafe: 2.8284271247461903
