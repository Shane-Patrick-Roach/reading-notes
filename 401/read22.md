# RecycleView


## What is recycleview?

---

- Recycleview maakes it eaasy to efficently display larage sets of data.
- You supply the data and define how each item looks.
- RecyclerView recycles those individual elements.
- This reuse vastly improves performance, improving your app's responsiveness and reducing power consumption.


### What are the key classes?

- Different classes work together to build your dynamic list.
- RecyclerView is the ViewGroup that contains the views corresponding to your data.
- Each individual element in the list is defined by a view holder object. After the view holder is created, the RecyclerView binds it to its data. You define the view holder by extending RecyclerView.ViewHolder.
- The RecyclerView requests those views, and binds the views to their data, by calling methods in the adapter. You define the adapter by extending RecyclerView.Adapter.
- The layout manager arranges the individual elements in your list. You can use one of the layout managers provided by the RecyclerView library, or you can define your own. Layout managers are all based on the library's LayoutManager abstract class.


### Key steps for implementing recycleview

1. What is the list or grid going to look like?
2. Design how each element in the list is going to look and behave.
3. Define the adapter that associates your data with the viewholder views.


## Resources/Citations

---

- [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview#java)
