# Value-serialisation-
 
/* Boolean */ JSON.stringify(true) // 'true'
/* Number */ JSON.stringify(12) // '12'
/* String */ JSON.stringify('foo') // '"foo"'
/* Object */ JSON.stringify({}) // '{}'
 JSON.stringify({foo: 'baz'}) // '{"foo": "baz"}'
/* Array */ JSON.stringify([1, true, 'foo']) // '[1, true, "foo"]'
/* Date */ JSON.stringify(new Date()) // '"2016-08-06T17:25:23.588Z"'
/* Symbol */ JSON.stringify({x:Symbol()}) // '{}
