<Type Name="AzureActiveDirectory" FullName="Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory">
  <TypeSignature Language="C#" Value="public class AzureActiveDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureActiveDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureActiveDirectory" />
  <TypeSignature Language="F#" Value="type AzureActiveDirectory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Einstellungen zum Aktivieren der AAD-Authentifizierung auf dem cluster
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureActiveDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureActiveDirectory-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureActiveDirectory (string tenantId = null, string clusterApplication = null, string clientApplication = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string tenantId, string clusterApplication, string clientApplication) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tenantId As String = null, Optional clusterApplication As String = null, Optional clientApplication As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory : string * string * string -&gt; Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory (tenantId, clusterApplication, clientApplication)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="clusterApplication" Type="System.String" />
        <Parameter Name="clientApplication" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tenantId">Azure active Directory-Mandanten-id</param>
        <param name="clusterApplication">Azure active Directory-Cluster-Anwendungs-id</param>
        <param name="clientApplication">Azure active Directory-Client-Anwendungs-id</param>
        <summary>
            Initialisiert eine neue Instanz der AzureActiveDirectory-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientApplication">
      <MemberSignature Language="C#" Value="public string ClientApplication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientApplication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.ClientApplication" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientApplication As String" />
      <MemberSignature Language="F#" Value="member this.ClientApplication : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.ClientApplication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientApplication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Id des Azure active Directory Client-Anwendung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterApplication">
      <MemberSignature Language="C#" Value="public string ClusterApplication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterApplication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.ClusterApplication" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterApplication As String" />
      <MemberSignature Language="F#" Value="member this.ClusterApplication : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.ClusterApplication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clusterApplication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Azure active Directory-Cluster-Anwendungs-id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Azure active Directory-Mandanten-id
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>