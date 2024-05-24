def rose_with_stars():
    rose = [
        '  *  ',
        '***  ',
        '***  ',
        '***** ',
        '***** ',
        '***  ',
        '***  ',
        '  *  '
    ]
    for petal in rose:
        print(petal + ' ' + petal)
    print(' ***  ')
    print('*** ***')
    print('*** ***')
    print(' ***  ')

rose_with_stars()


