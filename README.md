
# react-native-infinite-listview

A React Native ListView completely written in js, support refresh control and infinite scrolling

## Installation

`$ npm install react-native-infinite-listview --save`

## Usage
```javascript
import {InfiniteListview} from 'react-native-infinite-listview';

render() {
  return (
    <InfiniteListView
      style={{ flex: 1 }}
      dataArray={this.state.listItems}
      renderRow={this.renderRow}
      onRefresh={this.onRefresh}
      isRefreshing={this.state.isRefreshing}
      canLoadMore={this.canLoadMoreContent}
      isLoadingMore={this.state.isLoadingMore}
      onLoadMore={this.onLoadMore}
    />
  );
}

```
See more in Sample project