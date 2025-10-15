**Bright DEMO font**

**alinore font**

**aurora font**

**westack font**

**kaoly font**



**Industry use of data steps: https://chatgpt.com/share/68b68118-e28c-8013-b90e-ab2a43194bc5**



**Matplotlib**

1. plot(a,b, marker="o", color="r")
2. barh(a,b,color='r')
3. bar(a,b,color='r')
4. boxplot(df\["Maths"])
5. df.plot(kind='box', subplots=True, layout=(2,6), figsize=(10,10))
6. violinplot(df\['a'])
7. violinplot(df)
8. scatter(df\['a'], df\['b'], marker='\*')
9. plt.stackplot(x, y1, y2, labels=\['y1', 'y2'])
10. plt.hist(data, bins=10, color='g')
11. plt.pie(values, labels=labels, autopct='%1.1f%%')
12. plt.fill\_between(x, y)
13. plt.stem(x, y)
14. plt.errorbar(x, y, yerr=error)
15. plt.axhline(y=0.5)
16. plt.axvline(x=2)
17. plt.imshow(img)











**Saborn**

1. stripplot(x=x, y=y)
2. violinplot(x="Salary", data=df)
3. stripplot(x='spe', y='wis', data=a, palette='set1')
4. countplot(a\['d'], palette='viridis')
5. catplot(x='cla', y='sur', kind='bar', data=a, hue='sex')
6. histplot(x='t\_bill', data=a, bins=5)
7. displot(a\['tip'], kde=True)
8. kdeplot(a\['t\_bill'])
9. jointplot(x='a', y='b', data=a)
10. jointplot(data=a)
11. boxplot(a, x='d', y='b\_t', hue='smoker')
12. pairplot(a)
13. scatterplot(a, x='mpg', y='hp')
14. lineplot(a, x='mpg', y='hp')
15. relpkot(a, x='mpg', y='hp')
16. regplot(a, x='mpg', y='hp')
17. lmplot(x='distance', y='fare', data=a, hue='payment')
18. heatmap(a)
19. heatmap(a.isnull())
20. swarmplot(x='day', y='total\_bill', data=df)
21. clustermap(df.corr(), annot=True)
22. g = sns.FacetGrid(df, col="sex", row="smoker")
23.  	- g.map(sns.scatterplot, "total\_bill", "tip")
24. sns.ecdfplot(data=df, x="total\_bill")
25. sns.rugplot(df\['total\_bill'])



**==================================================================**



xlabel('a')

ylabel('b')

title('scs')

show()

