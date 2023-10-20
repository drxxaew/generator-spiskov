months = [
    {'id': 1, 'full_name':'март март март'},
    {'id': 2, 'full_name':'апрель апрель апрель'},
    {'id':3, 'full_name':'май май май'}
]

months_new = [month['full_name'] for month in months if len(month['full_name'].split()[1]) > 3]

print(months_new)
