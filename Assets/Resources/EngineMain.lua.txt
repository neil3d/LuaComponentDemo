-- 加载常用的Unity接口
luanet.load_assembly('UnityEngine')
luanet.load_assembly('Assembly-CSharp')

--导入引擎常用的class
Debug = luanet.import_type('UnityEngine.Debug')
GameObject = luanet.import_type('UnityEngine.GameObject')
Transform = luanet.import_type('UnityEngine.Transform')
Vector3 = luanet.import_type('UnityEngine.Vector3')
Time = luanet.import_type('UnityEngine.Time')

--导入游戏项目常用的组件
LuaComponent = luanet.import_type('LuaComponent')