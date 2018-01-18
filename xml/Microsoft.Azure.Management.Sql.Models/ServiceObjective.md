<Type Name="ServiceObjective" FullName="Microsoft.Azure.Management.Sql.Models.ServiceObjective">
  <TypeSignature Language="C#" Value="public class ServiceObjective : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceObjective extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ServiceObjective" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceObjective&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ServiceObjective = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c2943-101">Stellt einen Zielpunkt Datenbank dar.</span><span class="sxs-lookup"><span data-stu-id="c2943-101">Represents a database service objective.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjective ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceObjective.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2943-102">Initialisiert eine neue Instanz der ServiceObjective-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2943-102">Initializes a new instance of the ServiceObjective class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceObjective (string id = null, string name = null, string type = null, string serviceObjectiveName = null, bool isDefault = false, bool isSystem = false, string description = null, bool enabled = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string serviceObjectiveName, bool isDefault, bool isSystem, string description, bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ServiceObjective.#ctor(System.String,System.String,System.String,System.String,System.Boolean,System.Boolean,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional serviceObjectiveName As String = null, Optional isDefault As Boolean = false, Optional isSystem As Boolean = false, Optional description As String = null, Optional enabled As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ServiceObjective : string * string * string * string * bool * bool * string * bool -&gt; Microsoft.Azure.Management.Sql.Models.ServiceObjective" Usage="new Microsoft.Azure.Management.Sql.Models.ServiceObjective (id, name, type, serviceObjectiveName, isDefault, isSystem, description, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="serviceObjectiveName" Type="System.String" />
        <Parameter Name="isDefault" Type="System.Boolean" />
        <Parameter Name="isSystem" Type="System.Boolean" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c2943-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="c2943-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="c2943-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c2943-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="c2943-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="c2943-105">Resource type.</span></span></param>
        <param name="serviceObjectiveName"><span data-ttu-id="c2943-106">Der Name für dieses dienstziel.</span><span class="sxs-lookup"><span data-stu-id="c2943-106">The name for the service objective.</span></span></param>
        <param name="isDefault"><span data-ttu-id="c2943-107">Ruft ab, ob das SLO auf das standarddienstziel ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-107">Gets whether the service level objective is the default service objective.</span></span></param>
        <param name="isSystem"><span data-ttu-id="c2943-108">Ruft ab, ob der Servicelevel-Zielpunkt ein systemdienstziel ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-108">Gets whether the service level objective is a system service objective.</span></span></param>
        <param name="description"><span data-ttu-id="c2943-109">Die Beschreibung für den Servicelevel-Zielpunkt.</span><span class="sxs-lookup"><span data-stu-id="c2943-109">The description for the service level objective.</span></span></param>
        <param name="enabled"><span data-ttu-id="c2943-110">Ruft ab, ob der Servicelevel-Zielpunkt aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-110">Gets whether the service level objective is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="c2943-111">Initialisiert eine neue Instanz der ServiceObjective-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c2943-111">Initializes a new instance of the ServiceObjective class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjective.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjective.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2943-112">Ruft die Beschreibung für den Servicelevel-Zielpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="c2943-112">Gets the description for the service level objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjective.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjective.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2943-113">Ruft ab, ob der Servicelevel-Zielpunkt aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-113">Gets whether the service level objective is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefault">
      <MemberSignature Language="C#" Value="public bool IsDefault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjective.IsDefault" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefault As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefault : bool" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjective.IsDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefault")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2943-114">Ruft ab, ob das SLO auf das standarddienstziel ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-114">Gets whether the service level objective is the default service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSystem">
      <MemberSignature Language="C#" Value="public bool IsSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjective.IsSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSystem As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSystem : bool" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjective.IsSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSystem")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2943-115">Ruft ab, ob der Servicelevel-Zielpunkt ein systemdienstziel ist.</span><span class="sxs-lookup"><span data-stu-id="c2943-115">Gets whether the service level objective is a system service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string ServiceObjectiveName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ServiceObjective.ServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceObjectiveName : string" Usage="Microsoft.Azure.Management.Sql.Models.ServiceObjective.ServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2943-116">Ruft den Namen für dieses dienstziel.</span><span class="sxs-lookup"><span data-stu-id="c2943-116">Gets the name for the service objective.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>