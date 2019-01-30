# change_read_error_message
try and except blocks

def change_read():

    book_id = ui.get_book_id()
    try:                        
       book = store.get_book(book_id)
    else
       new_read = ui.get_read_value()
       store.set_book_read(book_id, new_read)

    except IOError:
        print('The book is not in Store!', e.errno))
    except:   
    print ("Unexpected error")
