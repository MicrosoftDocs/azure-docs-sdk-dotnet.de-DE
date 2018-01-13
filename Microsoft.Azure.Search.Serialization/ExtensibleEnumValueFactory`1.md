<Type Name="ExtensibleEnumValueFactory&lt;T&gt;" FullName="Microsoft.Azure.Search.Serialization.ExtensibleEnumValueFactory&lt;T&gt;">
  <TypeSignature Language="C#" Value="public delegate T ExtensibleEnumValueFactory&lt;T&gt;(string name) where T : ExtensibleEnum&lt;T&gt;;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ExtensibleEnumValueFactory`1&lt;(class Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;!T&gt;) T&gt; extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Serialization.ExtensibleEnumValueFactory`1" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ExtensibleEnumValueFactory(Of T)(name As String) As T " />
  <TypeSignature Language="F#" Value="type ExtensibleEnumValueFactory&lt;'T (requires 'T :&gt; ExtensibleEnum&lt;'T&gt;)&gt; = delegate of string -&gt; 'T" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;T&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="name" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>T</ReturnType>
  </ReturnValue>
  <Docs>
    <typeparam name="T">Der Typ des ExtensibleEnum zurückgegeben.</typeparam>
    <param name="name">Der Enum-Wert, um zu suchen oder erstellen.</param>
    <summary>
            Der Delegattyp für eine Factorymethode, die erstellt oder sucht eine ExtensibleEnum-Instanz aus einer angegebenen Zeichenfolge.
            </summary>
    <returns>Eine Instanz des Typs T.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>