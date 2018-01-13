<Type Name="TableQueryableExtensions" FullName="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions">
  <TypeSignature Language="C#" Value="public static class TableQueryableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed TableQueryableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableQueryableExtensions" />
  <TypeSignature Language="F#" Value="type TableQueryableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Satz von Erweiterungsmethoden für Objekte vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AsTableQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; AsTableQuery&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; AsTableQuery&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.AsTableQuery``1(System.Linq.IQueryable{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AsTableQuery(Of TElement) (query As IQueryable(Of TElement)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member AsTableQuery : System.Linq.IQueryable&lt;'Element&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.AsTableQuery query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</param>
        <summary>
            Gibt an, dass eine Abfrage zurückgegeben werden, als ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt.
            </summary>
        <returns>Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="Resolve&lt;TElement,TResolved&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TResolved&gt; Resolve&lt;TElement,TResolved&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResolved&gt; resolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TResolved&gt; Resolve&lt;TElement, TResolved&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResolved&gt; resolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.Resolve``2(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resolve(Of TElement, TResolved) (query As IQueryable(Of TElement), resolver As EntityResolver(Of TResolved)) As TableQuery(Of TResolved)" />
      <MemberSignature Language="F#" Value="static member Resolve : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Resolved&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Resolved&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.Resolve (query, resolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TResolved&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
        <TypeParameter Name="TResolved" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResolved&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResolved">Der Typ des Konfliktlösers.</typeparam>
        <param name="query">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</param>
        <param name="resolver">Der Typ der Entitäten-Resolver <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />.</param>
        <summary>
            Gibt eine Entitäten-Resolver für die Abfrage an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> mit den angegebenen Konfliktlöser.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithContext&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; WithContext&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; WithContext&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithContext``1(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WithContext : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithContext (query, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> für die Abfrage.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt mit den angegebenen Vorgangskontext.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithOptions&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; WithOptions&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; WithOptions&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithOptions``1(System.Linq.IQueryable{``0},Microsoft.WindowsAzure.Storage.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WithOptions(Of TElement) (query As IQueryable(Of TElement), options As TableRequestOptions) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member WithOptions : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.Queryable.TableQueryableExtensions.WithOptions (query, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Eine Abfrage, die implementiert <see cref="T:System.Linq.IQueryable`1" />.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <summary>
            Gibt einen Satz von <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> mit dem die Abfrage ausgeführt wird.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> Objekt, für die angegebene Anforderung Optionen festgelegt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
  </Members>
</Type>