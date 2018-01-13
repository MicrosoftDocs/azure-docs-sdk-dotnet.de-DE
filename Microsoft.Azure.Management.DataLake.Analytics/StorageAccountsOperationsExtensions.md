<Type Name="StorageAccountsOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StorageAccountsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorageAccountsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorageAccountsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StorageAccountsOperationsExtensions = class" />
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
            Erweiterungsmethoden für StorageAccountsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static void Add (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Add(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Add (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, parameters As AddStorageAccountParameters)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Add (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, das dem Azure Storage-Konto hinzugefügt.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Konto hinzufügen
            </param>
        <param name="parameters">
            Die Parameter, die den Zugriffsschlüssel und ein optionales Suffix für das Azure-Speicherkonto enthält.
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto hinzuzufügen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.AddAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
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
            Der Name des Data Lake Analytics-Kontos, das dem Azure Storage-Konto hinzugefügt.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Konto hinzufügen
            </param>
        <param name="parameters">
            Die Parameter, die den Zugriffsschlüssel und ein optionales Suffix für das Azure-Speicherkonto enthält.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto hinzuzufügen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Delete (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus dem Azure Storage-Konto entfernt werden soll.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Kontos entfernen
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto zu entfernen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
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
            Der Name des Data Lake Analytics-Kontos aus dem Azure Storage-Konto entfernt werden soll.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Kontos entfernen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das angegebene Data Lake Analytics-Konto um ein Azure Storage-Konto zu entfernen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo Get(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As StorageAccountInfo" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Get (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos aus der Azure-Speicher-Kontodetails abgerufen werden soll.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Kontos für die beim Abrufen von Details.
            </param>
        <summary>
            Ruft die angegebene Azure Storage-Konto, mit dem angegebenen Data Lake Analytics-Konto verknüpft.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; GetAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
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
            Der Name des Data Lake Analytics-Kontos aus der Azure-Speicher-Kontodetails abgerufen werden soll.
            </param>
        <param name="storageAccountName">
            Der Name des Azure Storage-Kontos für die beim Abrufen von Details.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Azure Storage-Konto, mit dem angegebenen Data Lake Analytics-Konto verknüpft.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer GetStorageContainer(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStorageContainer (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As StorageContainer" />
      <MemberSignature Language="F#" Value="static member GetStorageContainer : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainer (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos für das Blob-Container abgerufen werden sollen.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto aus dem Blob-Containers abgerufen.
            </param>
        <param name="containerName">
            Der Name des Azure-Speichercontainers abrufen
            </param>
        <summary>
            Ruft den angegebenen Azure-Speicher-Container, die der angegebene Data Lake Analytics und Azure Storage-Konten zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; GetStorageContainerAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageContainerAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.GetStorageContainerAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;GetStorageContainerAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
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
            Der Name des Data Lake Analytics-Kontos für das Blob-Container abgerufen werden sollen.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto aus dem Blob-Containers abgerufen.
            </param>
        <param name="containerName">
            Der Name des Azure-Speichercontainers abrufen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den angegebenen Azure-Speicher-Container, die der angegebene Data Lake Analytics und Azure Storage-Konten zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccount(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccount (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, Optional odataQuery As ODataQuery(Of StorageAccountInfo) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccount : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccount (operations, resourceGroupName, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
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
            Der Name des Data Lake Analytics-Kontos für den Azure Storage-Konten aufgelistet.
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
            Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountAsync (operations, resourceGroupName, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
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
            Der Name des Data Lake Analytics-Kontos für den Azure Storage-Konten aufgelistet.
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
            Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; ListByAccountNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByAccountNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; ListByAccountNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByAccountNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListByAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListByAccountNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Ruft ab der ersten Seite des Azure-Speicherkonten, wenn vorhanden, um das angegebene Data Lake Analytics-Konto verknüpft. Die Antwort enthält einen Link zur nächsten Seite, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokens">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokens(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokens (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, containerName As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokens : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokens (operations, resourceGroupName, accountName, storageAccountName, containerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos, das aus dem Azure Storage-Konto-SAS-Token angefordert wird.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto für das das SAS-Token angefordert wird.
            </param>
        <param name="containerName">
            Der Name des Azure-Speichercontainers an, für die das SAS-Token angefordert wird.
            </param>
        <summary>
            Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, string containerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensAsync (operations, resourceGroupName, accountName, storageAccountName, containerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
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
            Der Name des Data Lake Analytics-Kontos, das aus dem Azure Storage-Konto-SAS-Token angefordert wird.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto für das das SAS-Token angefordert wird.
            </param>
        <param name="containerName">
            Der Name des Azure-Speichercontainers an, für die das SAS-Token angefordert wird.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt; ListSasTokensNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSasTokensNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of SasTokenInfo)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt; ListSasTokensNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSasTokensNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListSasTokensNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListSasTokensNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Ruft das SAS-Token, die die angegebene Data Lake Analytics und Azure Storage-Konto und Container Kombination zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainers(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainers (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainers : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainers (operations, resourceGroupName, accountName, storageAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Kontos für den auf Azure-Speicher-Blob-Listencontainer.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto aus dem Blob-Container aufgelistet.
            </param>
        <summary>
            Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet. Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersAsync (operations, resourceGroupName, accountName, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
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
            Der Name des Data Lake Analytics-Kontos für den auf Azure-Speicher-Blob-Listencontainer.
            </param>
        <param name="storageAccountName">
            Der Name des Azure-Speicherkonto aus dem Blob-Container aufgelistet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet. Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt; ListStorageContainersNext(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListStorageContainersNext (operations As IStorageAccountsOperations, nextPageLink As String) As IPage(Of StorageContainer)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNext : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet. Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; ListStorageContainersNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListStorageContainersNextAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.ListStorageContainersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;ListStorageContainersNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
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
            Listet die Azure-Speichercontainer, soweit vorhanden, die der angegebenen Kombination der Data Lake Analytics und Azure Storage-Konto zugeordnet. Die Antwort enthält einen Link zur nächsten Seite der Ergebnisse, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static void Update (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Update(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Update (operations As IStorageAccountsOperations, resourceGroupName As String, accountName As String, storageAccountName As String, Optional parameters As UpdateStorageAccountParameters = null)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.Update (operations, resourceGroupName, accountName, storageAccountName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name des Azure-Ressourcengruppe, die das Data Lake Analytics-Konto enthält.
            </param>
        <param name="accountName">
            Der Name des Data Lake Analytics-Konto so ändern Sie Speicherkonten in
            </param>
        <param name="storageAccountName">
            Azure Storage-Kontos ändern
            </param>
        <param name="parameters">
            Die Parameter, enthält das Zugriffsschlüssel und das Suffix, um das Speicherkonto mit, zu aktualisieren, sofern vorhanden. Übergeben nichts führt keine Änderung.
            </param>
        <summary>
            Aktualisiert das Data Lake Analytics-Konto, um die Azure-Speicher-Blob-Kontodetails, wie z. B. die Zugriffstaste und/oder-Suffix ersetzen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations operations, string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, storageAccountName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.StorageAccountsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
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
            Der Name des Data Lake Analytics-Konto so ändern Sie Speicherkonten in
            </param>
        <param name="storageAccountName">
            Azure Storage-Kontos ändern
            </param>
        <param name="parameters">
            Die Parameter, enthält das Zugriffsschlüssel und das Suffix, um das Speicherkonto mit, zu aktualisieren, sofern vorhanden. Übergeben nichts führt keine Änderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Data Lake Analytics-Konto, um die Azure-Speicher-Blob-Kontodetails, wie z. B. die Zugriffstaste und/oder-Suffix ersetzen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>