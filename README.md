# Iowa_Liquor
Iowa Liquor Dataset, mostly cleaned

## File download
csv_file = '/iowa_liquor_clean_1k.csv' | csv_file = '/iowa_liquor_clean_10k.csv'

df = pd.read_csv(csv_file,
        dtype = {'year':np.int16, 'month':np.int8, 'day':np.int8,
        'store_number':np.int16, 'county_number':np.int8, 'item_number':np.int32,
        'pack':np.int16, 'bottle_vol':np.int64, 'bottle_cost':np.float32,
        'state_bottle_retail':np.float32, 'bottles_sold':np.int16, 'sale':np.float32,
        'vol_sold':np.float32, 'bottles_sold':np.int16,
        'category':np.int32, 'store_subnumber':np.int16, 'zip_code':np.int16,
        'vendor_number':np.int16
        })
