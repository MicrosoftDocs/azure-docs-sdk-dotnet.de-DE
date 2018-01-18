<Type Name="TypeCheckFunctionsExtensions" FullName="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions">
  <TypeSignature Language="C#" Value="public static class TypeCheckFunctionsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TypeCheckFunctionsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TypeCheckFunctionsExtensions" />
  <TypeSignature Language="F#" Value="type TypeCheckFunctionsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2d1b3-101">Geben Sie Methoden für die Überprüfung des Typs.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-101">Provide methods for type checking.</span></span>
            <span data-ttu-id="2d1b3-102">Diese Methoden in LINQ-Ausdrücke nur verwendet werden sollen, und werden auf dem Server ausgewertet werden.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-102">These methods are to be used in LINQ expressions only and will be evaluated on server.</span></span>
            <span data-ttu-id="2d1b3-103">Es ist keine Implementierung, die in der Clientbibliothek bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-103">There's no implementation provided in the client library.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IsDefined">
      <MemberSignature Language="C#" Value="public static bool IsDefined (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDefined(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsDefined(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsDefined (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDefined : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsDefined obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="2d1b3-104">Bestimmt, ob eine bestimmte Eigenschaft oder nicht definiert ist.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-104">Determines if a certain property is defined or not.</span></span>
            </summary>
        <returns><span data-ttu-id="2d1b3-105">Gibt "true" Wenn diese Eigenschaft definiert ist, andernfalls "false" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-105">Returns true if this property is defined otherwise returns false.</span></span></returns>
        <remarks />
        <example>
          <code><![CDATA[
            var isDefinedQuery = documents.Where(document => document.Name.IsDefined());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsNull">
      <MemberSignature Language="C#" Value="public static bool IsNull (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsNull(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsNull(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsNull (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsNull : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsNull obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="2d1b3-106">Bestimmt, ob eine bestimmte Eigenschaft null ist.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-106">Determines if a certain property is null or not.</span></span>
            </summary>
        <returns><span data-ttu-id="2d1b3-107">Gibt true zurück, wenn diese Eigenschaft null ist, andernfalls "false" zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-107">Returns true if this property is null otherwise returns false.</span></span></returns>
        <remarks />
        <example>
          <code><![CDATA[
            var isNullQuery = documents.Where(document => document.Name.IsNull());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsPrimitive">
      <MemberSignature Language="C#" Value="public static bool IsPrimitive (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsPrimitive(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsPrimitive(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsPrimitive (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsPrimitive : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsPrimitive obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="2d1b3-108">Bestimmt, ob eine bestimmte Eigenschaft des Premitive JSON-Typ ist.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-108">Determines if a certain property is of premitive JSON type.</span></span>
            </summary>
        <returns><span data-ttu-id="2d1b3-109">Gibt true zurück, wenn diese Eigenschaft null ist, andernfalls "false" zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="2d1b3-109">Returns true if this property is null otherwise returns false.</span></span></returns>
        <remarks>
            <span data-ttu-id="2d1b3-110">Premitive JSON-Typen (Double, String, Boolean und Null)</span><span class="sxs-lookup"><span data-stu-id="2d1b3-110">Premitive JSON types (Double, String, Boolean and Null)</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            var isPrimitiveQuery = documents.Where(document => document.Name.IsPrimitive());
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>