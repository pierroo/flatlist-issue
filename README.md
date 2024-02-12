<FlatList
            data={LIST}
            renderItem={renderItem}
            keyExtractor={(e) => e.id}
            getItemLayout={getItemLayout}
            // initialNumToRender={0} => this one breaks the UI, nothing displays if 0, 10 will display otherwise regardless of true length
            />
