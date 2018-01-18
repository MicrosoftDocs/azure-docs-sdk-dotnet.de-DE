<Type Name="ContainerServiceServicePrincipalProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceServicePrincipalProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceServicePrincipalProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceServicePrincipalProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceServicePrincipalProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3776a-101">Informationen zu principal Dienstidentität für den Cluster zum Bearbeiten von Azure-APIs verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="3776a-101">Information about a service principal identity for the cluster to use for manipulating Azure APIs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceServicePrincipalProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3776a-102">Initialisiert eine neue Instanz der ContainerServiceServicePrincipalProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3776a-102">Initializes a new instance of the ContainerServiceServicePrincipalProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceServicePrincipalProfile (string clientId, string secret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, secret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile : string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile (clientId, secret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="secret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="3776a-103">Die ID für den Dienstprinzipal.</span><span class="sxs-lookup"><span data-stu-id="3776a-103">The ID for the service principal.</span></span></param>
        <param name="secret"><span data-ttu-id="3776a-104">Die geheimen Kennworts, die dem Dienstprinzipal zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3776a-104">The secret password associated with the service principal.</span></span></param>
        <summary>
            <span data-ttu-id="3776a-105">Initialisiert eine neue Instanz der ContainerServiceServicePrincipalProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3776a-105">Initializes a new instance of the ContainerServiceServicePrincipalProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="clientId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3776a-106">Ruft ab oder legt die ID für den Dienst principal.</span><span class="sxs-lookup"><span data-stu-id="3776a-106">Gets or sets the ID for the service principal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Secret">
      <MemberSignature Language="C#" Value="public string Secret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Secret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.Secret" />
      <MemberSignature Language="VB.NET" Value="Public Property Secret As String" />
      <MemberSignature Language="F#" Value="member this.Secret : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.Secret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secret")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3776a-107">Ruft ab oder legt die geheimen Kennworts, die dem Dienstprinzipal zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3776a-107">Gets or sets the secret password associated with the service principal.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceServicePrincipalProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceServicePrincipalProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3776a-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3776a-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3776a-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3776a-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>