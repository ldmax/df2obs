## A tool to convert DataFrame to a list of objects of some class or vice versa
  - Signature will look like
  ```python
    def df2obs(df: pd.DataFrame, clazz: Any) -> List[Any]
  ```
  or
  ```python
    def obs2df(obs: List[Any]) -> pd.DataFrame
  ```
  - User need to define mapping between DataFrame columns and class attributes in class definition in a syntax similar to SQLAlchemy
  - This tool will inspect and automatically create list of objects from DataFrame or vice versa
