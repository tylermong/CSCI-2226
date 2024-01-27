def conjuction(p, q):
    return p and q

def disjuction(p, q):
    return p or q

def exclusiveOr(p, q):
    return p^q

def conditional(p, q):
    if p and not q:
        return False
    else:
        return True

def biconditional(p, q):
    if (p and q) or (not p and not q):
        return True
    else:
        return False

def negation(p):
    return not p

def testTT():
    a = True
    b = True
    print("\na = true | b = true")
    print("Conjuction: ", conjuction(a, b))
    print("Disjuction: ", disjuction(a, b))
    print("Exclusive Or: ", exclusiveOr(a, b))
    print("Conditional: ", conditional(a, b))
    print("Biconditional: ", biconditional(a, b))

def testTF():
    a = True
    b = False
    print("\na = true | b = false")
    print("Conjuction: ", conjuction(a, b))
    print("Disjuction: ", disjuction(a, b))
    print("Exclusive Or: ", exclusiveOr(a, b))
    print("Conditional: ", conditional(a, b))
    print("Biconditional: ", biconditional(a, b))

def testFT():
    a = False
    b = True
    print("\na = false | b = true")
    print("Conjuction: ", conjuction(a, b))
    print("Disjuction: ", disjuction(a, b))
    print("Exclusive Or: ", exclusiveOr(a, b))
    print("Conditional: ", conditional(a, b))
    print("Biconditional: ", biconditional(a, b))

def testFF():
    a = False
    b = False
    print("\na = false | b = false")
    print("Conjuction: ", conjuction(a, b))
    print("Disjuction: ", disjuction(a, b))
    print("Exclusive Or: ", exclusiveOr(a, b))
    print("Conditional: ", conditional(a, b))
    print("Biconditional: ", biconditional(a, b))

def printTableFunction1():
    for p in (True, False):
        for q in (True, False):
            print("%10s%10s%10s" % (p, q, conditional(negation(p), q)))
    print("\n")

def printTableFunction2():
    for p in (True, False):
        for q in (True, False):
            print("%10s%10s%10s" % (p, q, conjuction(p, q)))
    print("\n")

def testAll():
    testTT()
    testTF()
    testFT()
    testFF()

testAll()
printTableFunction1()
printTableFunction2()
