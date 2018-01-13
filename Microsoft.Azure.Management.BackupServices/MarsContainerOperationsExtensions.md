<Type Name="MarsContainerOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MarsContainerOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MarsContainerOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MarsContainerOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MarsContainerOperationsExtensions = class" />
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
    <Member MemberName="EnableMarsContainerReregistration">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse EnableMarsContainerReregistration(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistration : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistration (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerId">
            Erforderlich. MARS-Container-ID.
            </param>
        <param name="enableReregistrationRequest">
            Erforderlich. Aktivieren Sie die Anforderung für eine erneute Registrierung.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Der Container eine erneute Registrierung zu aktivieren.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMarsContainerReregistrationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member EnableMarsContainerReregistrationAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.EnableMarsContainerReregistrationAsync (operations, resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerId">
            Erforderlich. MARS-Container-ID.
            </param>
        <param name="enableReregistrationRequest">
            Erforderlich. Aktivieren Sie die Anforderung für eine erneute Registrierung.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Der Container eine erneute Registrierung zu aktivieren.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByType(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByType : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByType (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerType">
            Erforderlich. Der Typ des Containers.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.
            </summary>
        <returns>
            Die Liste der Microsoft Azure Recovery Services (MARS)-Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyName">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse ListMarsContainersByTypeAndFriendlyName(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyName : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyName (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerType">
            Erforderlich. Der Typ des Containers.
            </param>
        <param name="friendlyName">
            Erforderlich. Anzeigename des Containers.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.
            </summary>
        <returns>
            Die Liste der Microsoft Azure Recovery Services (MARS)-Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAndFriendlyNameAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAndFriendlyNameAsync (operations, resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerType">
            Erforderlich. Der Typ des Containers.
            </param>
        <param name="friendlyName">
            Erforderlich. Anzeigename des Containers.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.
            </summary>
        <returns>
            Die Liste der Microsoft Azure Recovery Services (MARS)-Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListMarsContainersByTypeAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.ListMarsContainersByTypeAsync (operations, resourceGroupName, resourceName, containerType, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerType">
            Erforderlich. Der Typ des Containers.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.
            </summary>
        <returns>
            Die Liste der Microsoft Azure Recovery Services (MARS)-Container.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UnregisterMarsContainer(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainer : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainer (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerId">
            Erforderlich. MARS-Container-ID.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Aufheben der Registrierung des Containers.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync (this Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync(class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations operations, string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync(Microsoft.Azure.Management.BackupServices.IMarsContainerOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UnregisterMarsContainerAsync : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.MarsContainerOperationsExtensions.UnregisterMarsContainerAsync (operations, resourceGroupName, resourceName, containerId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.
            </param>
        <param name="resourceGroupName">
            Erforderlich.
            </param>
        <param name="resourceName">
            Erforderlich.
            </param>
        <param name="containerId">
            Erforderlich. MARS-Container-ID.
            </param>
        <param name="customRequestHeaders">
            Optional. Header Anforderungsparameter.
            </param>
        <summary>
            Aufheben der Registrierung des Containers.
            </summary>
        <returns>
            Die Definition einer Operation-Antwort.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>