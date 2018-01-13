<Type Name="DataLakeStoreAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataLakeStoreAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataLakeStoreAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataLakeStoreAccountsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für DataLakeStoreAccountsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String, Optional parameters As AddDataLakeStoreParameters = null)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, dem das Data Lake-Speicher-Konto hinzugefügt.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des hinzuzufügenden Kontos Data Lake-Speicher.
            </param>
        <param name="parameters">
            Die Details des Kontos Data Lake-Speicher.
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto, um den zusätzlichen Data Lake-Speicher-Konten gehören.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, dem das Data Lake-Speicher-Konto hinzugefügt.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des hinzuzufügenden Kontos Data Lake-Speicher.
            </param>
        <param name="parameters">
            Die Details des Kontos Data Lake-Speicher.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto, um den zusätzlichen Data Lake-Speicher-Konten gehören.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus dem das Data Lake-Speicher-Konto entfernt werden soll.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des Kontos Data Lake-Speicher entfernen
            </param>
        <summary>
            Aktualisiert das Data Lake Analytics-Konto angegeben, um das angegebene Data Lake-Speicher-Konto zu entfernen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus dem das Data Lake-Speicher-Konto entfernt werden soll.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des Kontos Data Lake-Speicher entfernen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Data Lake Analytics-Konto angegeben, um das angegebene Data Lake-Speicher-Konto zu entfernen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, dataLakeStoreAccountName As String) As DataLakeStoreAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, dataLakeStoreAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, von dem die Kontodetails Data Lake-Speicher abgerufen werden soll.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des Data Lake-Speicher-Konto abrufen
            </param>
        <summary>
            Ruft die angegebene Data Lake-Speicher-Kontodetails in das angegebene Data Lake Analytics-Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, string dataLakeStoreAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, dataLakeStoreAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, von dem die Kontodetails Data Lake-Speicher abgerufen werden soll.
            </param>
        <param name="dataLakeStoreAccountName">
            Der Name des Data Lake-Speicher-Konto abrufen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Data Lake-Speicher-Kontodetails in das angegebene Data Lake Analytics-Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IDataLakeStoreAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of DataLakeStoreAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos für den Data Lake-Speicher-Konten aufgelistet.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="select">
            OData-Select-Anweisung. Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =. Optional.
            </param>
        <param name="count">
            Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true". Optional.
            </param>
        <summary>
            Ruft die erste Seite des Data Lake-Speicher-Konten, die dem angegebenen Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos für den Data Lake-Speicher-Konten aufgelistet.
            </param>
        <param name="odataQuery">
            OData-Parameter des Vorgangs angewendet.
            </param>
        <param name="select">
            OData-Select-Anweisung. Schränkt die Eigenschaften auf jeder Eintrag auf diejenigen angefordert, z. B. Kategorien? $select CategoryName, Beschreibung =. Optional.
            </param>
        <param name="count">
            Der boolesche Wert "true" oder "false", um eine Anzahl der übereinstimmenden Ressourcen enthalten, die mit den Ressourcen in der Antwort, z. B. Kategorien anzufordern? $count = "true". Optional.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die erste Seite des Data Lake-Speicher-Konten, die dem angegebenen Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IDataLakeStoreAccountsOperations, nextPageLink As String) As IPage(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft die erste Seite des Data Lake-Speicher-Konten, die dem angegebenen Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.DataLakeStoreAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die erste Seite des Data Lake-Speicher-Konten, die dem angegebenen Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>