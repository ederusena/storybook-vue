## Add JTableRow as its dependency, which will update our JTable package.json and generate a node_modules folder inside the JTable;

```shell
lerna add @ederusena/j-table-row --scope=@ederusena/j-table
```

# install
npm install @ederusena/j-table
# importing JTable automatically will bring JTableRow
import JTable from '@ederusena/j-table/JTable'