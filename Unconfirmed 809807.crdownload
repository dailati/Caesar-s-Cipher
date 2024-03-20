key = int(input("Enter the shift value: "))
cipher = "tqjzfxfdemcplvespwlhozteezdptkpazhpctylwwzespcnldpdzmdpcgptetnlxptdlhtnzybfpcpotetdmpeepcezncplepeslyezwplcyncpletyrtdesppddpynpzqwtqpldlcfwpxpyhzccjxzcplmzfehsleespjnlyedppeslylmzfehsleespjnlytetdpldtpcezqtyoxpyhszhtwwgzwfyeppcezotpeslyezqtyoeszdphszlcphtwwtyrezpyofcpaltyhtesaletpynp"

def pokemon(cipher, key):
    result=""
    for k in cipher:
            if k.isalpha():
                plain = ord(k) - key
                if plain < ord('a'):
                    plain += 26
                lol = chr(plain)
                result += lol
    print(result)
    return result

pokemon(cipher, key)