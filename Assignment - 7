
 words = ["eat", "tea", "tan", "ate", "nat", "bat"]
result = {"eat": [], "tan": [], "bat": []}

key_map = {key: ''.join(sorted(key)) for key in result}

for word in words:
    sorted_word = ''.join(sorted(word))
    for key, sorted_key in key_map.items():
        if sorted_word == sorted_key:
            result[key].append(word)
            break

print(result)

