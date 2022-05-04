# Shane Selinger

def s_dev(inputList):
    input_size = len(inputList)
    mean = sum(inputList) / input_size

    sdev = ( sum( (x - mean)**2 for x in inputList ) / input_size ) ** 0.5
    return sdev

temp_input = [ float(i) for i in input("> ").split(" ") ]

if s_dev(temp_input) > 1:
    print("NOT COMFY")
else:
    print("COMFY")
