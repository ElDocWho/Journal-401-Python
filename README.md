#Daily Journal

**Day 1**

I was in the hospital, so I did not have a lot of time to learn python this day.

**Day 2**

Still in the hospital.

**Day 3**

Out of the hospital but had to rest for the day becuase of the procedure at the hospital. 

**Day 4**

First day of class for me, a lot of info, a lot of catching up.

I learned about how to use pytest. I actually used it in an assignement we were working on today. Here is an example of the code:

@pytest.mark.parametrize('words_list,result', DICT_TEST)
def test_make_dict(words_list, result):
    """Make a test with list of words and making a dictionary for two consecutive words as key and third as value"""

    from trigrams import list_to_dict
    assert list_to_dict(words_list) == result

I foud it a lot easier than testing with JS. 

I also learned how use methods with lists like 

list.append()
list.reverse()
list.pop()
list.remove()