<Type Name="PolicySku" FullName="Microsoft.Azure.Management.ResourceManager.Models.PolicySku">
  <TypeSignature Language="C#" Value="public class PolicySku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolicySku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.PolicySku" />
  <TypeSignature Language="VB.NET" Value="Public Class PolicySku" />
  <TypeSignature Language="F#" Value="type PolicySku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f44ce-101">Die Richtlinie-Sku.</span><span class="sxs-lookup"><span data-stu-id="f44ce-101">The policy sku.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f44ce-102">Initialisiert eine neue Instanz der PolicySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f44ce-102">Initializes a new instance of the PolicySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolicySku (string name, string tier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySku.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional tier As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.PolicySku : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.PolicySku" Usage="new Microsoft.Azure.Management.ResourceManager.Models.PolicySku (name, tier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f44ce-103">Der Name der Richtlinie Sku.</span><span class="sxs-lookup"><span data-stu-id="f44ce-103">The name of the policy sku.</span></span> <span data-ttu-id="f44ce-104">Mögliche Werte sind A0 und A1.</span><span class="sxs-lookup"><span data-stu-id="f44ce-104">Possible values are A0 and A1.</span></span></param>
        <param name="tier"><span data-ttu-id="f44ce-105">Die Richtlinie Sku-Tarif.</span><span class="sxs-lookup"><span data-stu-id="f44ce-105">The policy sku tier.</span></span> <span data-ttu-id="f44ce-106">Mögliche Werte sind kostenlos "und" Standard.</span><span class="sxs-lookup"><span data-stu-id="f44ce-106">Possible values are Free and Standard.</span></span></param>
        <summary>
            <span data-ttu-id="f44ce-107">Initialisiert eine neue Instanz der PolicySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f44ce-107">Initializes a new instance of the PolicySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f44ce-108">Ruft ab oder legt den Namen der Richtlinie Sku.</span><span class="sxs-lookup"><span data-stu-id="f44ce-108">Gets or sets the name of the policy sku.</span></span> <span data-ttu-id="f44ce-109">Mögliche Werte sind A0 und A1.</span><span class="sxs-lookup"><span data-stu-id="f44ce-109">Possible values are A0 and A1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.PolicySku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.PolicySku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f44ce-110">Abrufen oder Festlegen der Richtlinie Sku-Tarif.</span><span class="sxs-lookup"><span data-stu-id="f44ce-110">Gets or sets the policy sku tier.</span></span> <span data-ttu-id="f44ce-111">Mögliche Werte sind kostenlos "und" Standard.</span><span class="sxs-lookup"><span data-stu-id="f44ce-111">Possible values are Free and Standard.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.PolicySku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="policySku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f44ce-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f44ce-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f44ce-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f44ce-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>