<Type Name="AzureMLLinkedService" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService">
  <TypeSignature Language="C#" Value="public class AzureMLLinkedService : Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureMLLinkedService extends Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureMLLinkedService&#xA;Inherits LinkedServiceTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureMLLinkedService = class&#xA;    inherit LinkedServiceTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.LinkedServiceTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureML")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure ML-Webdienst verknüpfter Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse "azuremllinkedservice".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureMLLinkedService (string mlEndpoint, string apiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mlEndpoint, string apiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mlEndpoint As String, apiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService (mlEndpoint, apiKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mlEndpoint" Type="System.String" />
        <Parameter Name="apiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mlEndpoint">To be added.</param>
        <param name="apiKey">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "azuremllinkedservice" mit erforderlichen Argumenten.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiKey">
      <MemberSignature Language="C#" Value="public string ApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiKey As String" />
      <MemberSignature Language="F#" Value="member this.ApiKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Die API-Schlüssel für den Zugriff auf den Endpunkt der Azure ML-Modell.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MlEndpoint">
      <MemberSignature Language="C#" Value="public string MlEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MlEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property MlEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.MlEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.MlEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Der Batch Execution REST-URL für einen Azure ML-Webdienst-Endpunkt.
            Der Endpunkt muss im Format: https://_Region_.services.azureml.net/workspaces/_Workspace_id_/Services /_Service_id _ /Aufträge? api-Version = 2.0"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalId">
      <MemberSignature Language="C#" Value="public string ServicePrincipalId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalId : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Die ID des dienstprinzipals, der zum Authentifizieren der ARM-basierten UpdateResourceEndpoint von einem Azure ML-Webdienst verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePrincipalKey">
      <MemberSignature Language="C#" Value="public string ServicePrincipalKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePrincipalKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePrincipalKey As String" />
      <MemberSignature Language="F#" Value="member this.ServicePrincipalKey : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.ServicePrincipalKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der Schlüssel des dienstprinzipals, der zum Authentifizieren der ARM-basierten UpdateResourceEndpoint von einem Azure ML-Webdienst verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tenant">
      <MemberSignature Language="C#" Value="public string Tenant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tenant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
      <MemberSignature Language="VB.NET" Value="Public Property Tenant As String" />
      <MemberSignature Language="F#" Value="member this.Tenant : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.Tenant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Der Name oder ID des Mandanten, zu dem der Dienstprinzipal gehört.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateResourceEndpoint">
      <MemberSignature Language="C#" Value="public string UpdateResourceEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateResourceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateResourceEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.UpdateResourceEndpoint : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureMLLinkedService.UpdateResourceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Die Aktualisierung Ressourcen REST-URL für einen Azure ML-Webdienst-Endpunkt.
            Der Endpunkt muss im Format: https://management.azureml.net/workspaces/_Workspace_id_/webservices/_Service_id_/endpoints/_EndpointName_.
            Schließen Sie diese Eigenschaft für die Aktualisierung des Endpunkts nach Umschulung mit <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureMLUpdateResourceActivity" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>