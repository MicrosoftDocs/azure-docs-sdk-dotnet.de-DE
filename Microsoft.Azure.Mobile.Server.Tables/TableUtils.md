<Type Name="TableUtils" FullName="Microsoft.Azure.Mobile.Server.Tables.TableUtils">
  <TypeSignature Language="C#" Value="public static class TableUtils" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TableUtils extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.TableUtils" />
  <TypeSignature Language="VB.NET" Value="Public Class TableUtils" />
  <TypeSignature Language="F#" Value="type TableUtils = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet verschiedene Hilfsprogramme und Hilfsmethoden für die Tabelle verwandte Funktionen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyDeletedFilter&lt;TData&gt;">
      <MemberSignature Language="C#" Value="public static System.Linq.IQueryable&lt;TData&gt; ApplyDeletedFilter&lt;TData&gt; (System.Linq.IQueryable&lt;TData&gt; query, bool includeDeleted) where TData : class, Microsoft.Azure.Mobile.Server.Tables.ITableData;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Linq.IQueryable`1&lt;!!TData&gt; ApplyDeletedFilter&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt;(class System.Linq.IQueryable`1&lt;!!TData&gt; query, bool includeDeleted) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.ApplyDeletedFilter``1(System.Linq.IQueryable{``0},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ApplyDeletedFilter(Of TData As {Class, ITableData}) (query As IQueryable(Of TData), includeDeleted As Boolean) As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="static member ApplyDeletedFilter : System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; * bool -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.ApplyDeletedFilter (query, includeDeleted)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TData">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TData&gt;" />
        <Parameter Name="includeDeleted" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <typeparam name="TData">Der Typ der Daten</typeparam>
        <param name="query">Die Abfrage zum Filtern</param>
        <param name="includeDeleted">Gibt an, ob der Filter festgelegt ist</param>
        <summary>
            Wendet den Filter auf gelöschte Datensätze, wenn <paramref name="includeDeleted" /> ist "true".
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedPropertyName">
      <MemberSignature Language="C#" Value="public static string DeletedPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DeletedPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.DeletedPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DeletedPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.DeletedPropertyName : string" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.DeletedPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <c>gelöschte</c> Eigenschaftsname.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNoQueryableLookupException">
      <MemberSignature Language="C#" Value="public static Exception GetNoQueryableLookupException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetNoQueryableLookupException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableLookupException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNoQueryableLookupException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetNoQueryableLookupException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableLookupException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType">Der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />-Typ.</param>
        <param name="method">Der Methodenname der wird unterstützt nicht.</param>
        <summary>
            Ruft eine <see cref="T:System.NotImplementedException" /> zeigt an, dass eine bestimmte <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> unterstützt keine <see cref="T:System.Linq.IQueryable`1" /> Suchvorgänge basierend.
            </summary>
        <returns>Ein neuer <see cref="T:System.NotImplementedException" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNoQueryableQueryException">
      <MemberSignature Language="C#" Value="public static Exception GetNoQueryableQueryException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetNoQueryableQueryException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableQueryException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNoQueryableQueryException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetNoQueryableQueryException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetNoQueryableQueryException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType">Der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />-Typ.</param>
        <param name="method">Der Methodenname der wird unterstützt nicht.</param>
        <summary>
            Ruft eine <see cref="T:System.NotImplementedException" /> zeigt an, dass eine angegebenen <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> unterstützt keine <see cref="T:System.Linq.IQueryable`1" /> basierten Abfragen.
            </summary>
        <returns>Ein neuer <see cref="T:System.NotImplementedException" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueryableOnlyLookupException">
      <MemberSignature Language="C#" Value="public static Exception GetQueryableOnlyLookupException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetQueryableOnlyLookupException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyLookupException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetQueryableOnlyLookupException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetQueryableOnlyLookupException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyLookupException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType">Der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />-Typ.</param>
        <param name="method">Der Methodenname der wird unterstützt nicht.</param>
        <summary>
            Ruft eine <see cref="T:System.NotImplementedException" /> zeigt an, dass eine bestimmte <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> unterstützt nur <see cref="T:System.Linq.IQueryable`1" /> Suchvorgänge basierend.
            </summary>
        <returns>Ein neuer <see cref="T:System.NotImplementedException" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueryableOnlyQueryException">
      <MemberSignature Language="C#" Value="public static Exception GetQueryableOnlyQueryException (Type domainManagerType, string method);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Exception GetQueryableOnlyQueryException(class System.Type domainManagerType, string method) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyQueryException(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetQueryableOnlyQueryException (domainManagerType As Type, method As String) As Exception" />
      <MemberSignature Language="F#" Value="static member GetQueryableOnlyQueryException : Type * string -&gt; Exception" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetQueryableOnlyQueryException (domainManagerType, method)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domainManagerType" Type="System.Type" />
        <Parameter Name="method" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domainManagerType">Der <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" />-Typ.</param>
        <param name="method">Der Methodenname der wird unterstützt nicht.</param>
        <summary>
            Ruft eine <see cref="T:System.NotImplementedException" /> zeigt an, dass eine angegebene <see cref="T:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1" /> unterstützt nur <see cref="T:System.Linq.IQueryable`1" /> basierten Abfragen.
            </summary>
        <returns>Ein neuer <see cref="T:System.NotImplementedException" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResultSize">
      <MemberSignature Language="C#" Value="public static int GetResultSize (System.Web.Http.OData.Query.ODataQueryOptions query, System.Web.Http.OData.Query.ODataQuerySettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 GetResultSize(class System.Web.Http.OData.Query.ODataQueryOptions query, class System.Web.Http.OData.Query.ODataQuerySettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetResultSize(System.Web.Http.OData.Query.ODataQueryOptions,System.Web.Http.OData.Query.ODataQuerySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetResultSize (query As ODataQueryOptions, settings As ODataQuerySettings) As Integer" />
      <MemberSignature Language="F#" Value="static member GetResultSize : System.Web.Http.OData.Query.ODataQueryOptions * System.Web.Http.OData.Query.ODataQuerySettings -&gt; int" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.GetResultSize (query, settings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
        <Parameter Name="settings" Type="System.Web.Http.OData.Query.ODataQuerySettings" />
      </Parameters>
      <Docs>
        <param name="query">To be added.</param>
        <param name="settings">To be added.</param>
        <summary>
            Ruft die effektive Abfrage Ergebnis Größe Bedeutung die maximale Anzahl von Elementen, die in einem einzelnen Abfrageergebnis enthalten auf der Seitengröße und die oberen Parameter in Grundlage der <paramref name="query" /> <paramref name="settings" />.
            </summary>
        <returns>Die effektive Seitengröße für die angegebene Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PageSize">
      <MemberSignature Language="C#" Value="public static int PageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 PageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.PageSize" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property PageSize As Integer" />
      <MemberSignature Language="F#" Value="member this.PageSize : int with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.PageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die maximale Anzahl der Datensätze, die in einem Abfrageergebnis zurückgegeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionPropertyName">
      <MemberSignature Language="C#" Value="public static string VersionPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string VersionPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.TableUtils.VersionPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property VersionPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.VersionPropertyName : string" Usage="Microsoft.Azure.Mobile.Server.Tables.TableUtils.VersionPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <c>Version</c> Eigenschaftsname.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>