n1 = float(input('What is Bitcoin price today?: '))
n2 = float(input('How much $ do you have?: '))
x = n2/n1
x = float('{:.7f}'.format(x))
print('You can buy:', x, 'BTC')
