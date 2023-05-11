# Write-a-Python-program-to-iterate-over-dictionaries-using-for-loops.
my_dict = {"key1": "value1", "key2": "value2", "key3": "value3"}
# Iterate over the keys of the dictionary
print("Iterating over keys:")
for key in my_dict:
print(key)
# Iterate over the values of the dictionary
print("\nIterating over values:")
for value in my_dict.values():
print(value)
# Iterate over the key-value pairs of the dictionary
print("\nIterating over key-value pairs:")
for key, value in my_dict.items():
print(f"{key}: {value}")
