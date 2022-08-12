# resources


```py
fig = px.line(temp, x = df.index, y = df.columns, title='title', width=1100, height=550, template="simple_white")

fig.update_layout(
    font_family="Times New Roman",
    legend=dict(
        title=None, orientation="h", y=1, yanchor="bottom", x=0.5, xanchor="center"
    ),
    yaxis={'visible': True, 'showticklabels': True},
    margin=dict(
        autoexpand=False,
        l=40,
        r=10,
        t=100,
    ),
    yaxis_title=None,
    xaxis_title=None,
    # hovermode="x unified"
)
fig.add_hline(y=45, opacity=1, line_width=2, line_dash='dash', line_color='Red')

fig.show()
```
