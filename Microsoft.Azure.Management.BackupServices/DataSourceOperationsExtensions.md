<Type Name="DataSourceOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourceOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableProtectionCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse DisableProtectionCSM (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse DisableProtectionCSM(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.DisableProtectionCSM(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member DisableProtectionCSM : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.DisableProtectionCSM (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <summary>
            Deaktivieren Sie den Schutz für die angegebene Element
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.DisableProtectionCSMAsync(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member DisableProtectionCSMAsync : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.DisableProtectionCSMAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <summary>
            Deaktivieren Sie den Schutz für die angegebene Element
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableProtectionCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse EnableProtectionCSM (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse EnableProtectionCSM(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.EnableProtectionCSM(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest)" />
      <MemberSignature Language="F#" Value="static member EnableProtectionCSM : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.EnableProtectionCSM (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <param name="csmparameters">
            Erforderlich. Set-Schutz-Anforderung Eingabe.
            </param>
        <summary>
            Aktivieren des Schutzes für Element angegeben.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.EnableProtectionCSMAsync(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest)" />
      <MemberSignature Language="F#" Value="static member EnableProtectionCSMAsync : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.EnableProtectionCSMAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <param name="csmparameters">
            Erforderlich. Set-Schutz-Anforderung Eingabe.
            </param>
        <summary>
            Aktivieren des Schutzes für Element angegeben.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse ListCSM (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse ListCSM(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.ListCSM(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSM : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.ListCSM (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="csmparameters">
            Optional. DataSource-Abfrageparameter.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste aller Datenquellen.
            </summary>
        <returns>
            Die Definition einer CSMProtectedItemListOperationResponse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.ListCSMAsync(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListCSMAsync : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.ListCSMAsync (operations, resourceGroupName, resourceName, csmparameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="csmparameters">
            Optional. DataSource-Abfrageparameter.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste aller Datenquellen.
            </summary>
        <returns>
            Die Definition einer CSMProtectedItemListOperationResponse.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProtectionCSM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UpdateProtectionCSM (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UpdateProtectionCSM(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.UpdateProtectionCSM(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest)" />
      <MemberSignature Language="F#" Value="static member UpdateProtectionCSM : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.UpdateProtectionCSM (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <param name="csmparameters">
            Erforderlich. Set-Schutz-Anforderung Eingabe.
            </param>
        <summary>
            Aktivieren des Schutzes für Element angegeben.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync (this Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync(class Microsoft.Azure.Management.BackupServices.IDataSourceOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.UpdateProtectionCSMAsync(Microsoft.Azure.Management.BackupServices.IDataSourceOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest)" />
      <MemberSignature Language="F#" Value="static member UpdateProtectionCSMAsync : Microsoft.Azure.Management.BackupServices.IDataSourceOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.DataSourceOperationsExtensions.UpdateProtectionCSMAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IDataSourceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IDataSourceOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <param name="containerName">
            Erforderlich. ContainerName.
            </param>
        <param name="itemName">
            Erforderlich. Elementname.
            </param>
        <param name="csmparameters">
            Erforderlich. Set-Schutz-Anforderung Eingabe.
            </param>
        <summary>
            Aktivieren des Schutzes für Element angegeben.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>