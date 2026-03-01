# Mid-Level Python Developer Interview Questions

## 🧠 Core Python

1.  What is the difference between `list`, `tuple`, and `set`
    internally?

2.  Explain mutable vs immutable objects with real examples.

3.  What happens in memory when you do:

    ``` python
    a = [1, 2, 3]
    b = a
    b.append(4)
    ```

4.  What is the difference between `deepcopy` and `shallow copy`?

5.  What is the difference between `is` and `==`?

6.  How does Python manage memory? What is reference counting?

7.  What is garbage collection in Python?

8.  What are generators? Why are they memory efficient?

9.  What is the difference between `yield` and `return`?

10. What is the difference between `@staticmethod`, `@classmethod`, and
    instance methods?

------------------------------------------------------------------------

## 🏗 OOP & Design

1.  What is Method Resolution Order (MRO)?
2.  Explain multiple inheritance in Python.
3.  What is the use of `super()`?
4.  What are abstract base classes?
5.  What is duck typing?
6.  What is the difference between composition and inheritance?
7.  How would you implement Singleton in Python?
8.  What are dunder methods? Give examples.

------------------------------------------------------------------------

## ⚙️ Advanced Python

1.  What are decorators? How do you create a custom decorator?
2.  What are closures?
3.  Explain LEGB rule.
4.  What is the difference between `*args` and `**kwargs`?
5.  What are context managers? How does `with` work?
6.  How does Python handle exceptions internally?
7.  What is the difference between `__new__` and `__init__`?
8.  What are metaclasses (conceptually)?
9.  What is monkey patching?
10. What is the Global Interpreter Lock (GIL)?

------------------------------------------------------------------------

## 🚀 Concurrency & Performance

1.  Difference between threading and multiprocessing?
2.  When would threading not improve performance?
3.  What is async/await?
4.  What is event loop?
5.  How do you optimize a slow Python function?
6.  How to profile Python code?
7.  What is lazy evaluation?

------------------------------------------------------------------------

## 🗄 Backend-Oriented

1.  How does Django handle request lifecycle?
2.  What happens when a Django view is called?
3.  Difference between WSGI and ASGI?
4.  What is middleware?
5.  What are Django signals?
6.  What is the N+1 query problem?
7.  How does `select_related` differ from `prefetch_related`?
8.  How does Celery work internally?
9.  What is idempotency in APIs?
10. How would you handle a long-running API request?

------------------------------------------------------------------------

## 🧨 Scenario-Based

1.  You have a function taking 8 seconds. How do you investigate?
2.  A Django API suddenly becomes slow in production. What steps do you
    take?
3.  You suspect a memory leak. What do you check?
4.  How do you design a rate limiter?
5.  How do you design a notification system?
6.  How do you secure JWT authentication?
7.  How do you design an audit logging system?

------------------------------------------------------------------------

## 🔥 Logical Python Question

What is the output of the following code?

``` python
def func(nums=[]):
    nums.append(1)
    return nums

print(func())
print(func())
print(func())
```
