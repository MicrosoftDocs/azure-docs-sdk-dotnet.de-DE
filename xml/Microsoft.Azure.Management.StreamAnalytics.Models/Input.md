<Type Name="Input" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.Input">
  <TypeSignature Language="C#" Value="public class Input : Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Input extends Microsoft.Azure.Management.StreamAnalytics.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
  <TypeSignature Language="VB.NET" Value="Public Class Input&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type Input = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8f93e-101">Ein Eingabeobjekt, enthält alle Informationen, die die benannte Eingabe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8f93e-101">An input object, containing all information associated with the named input.</span></span> <span data-ttu-id="8f93e-102">Alle Eingaben, die unter einem streamingauftrag enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="8f93e-102">All inputs are contained under a streaming job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Input ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Input.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8f93e-103">Initialisiert eine neue Instanz der Eingabe-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f93e-103">Initializes a new instance of the Input class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Input (string id = null, string name = null, string type = null, Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.Input.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional properties As InputProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.Input : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.Input (id, name, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8f93e-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="8f93e-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="8f93e-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="8f93e-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="8f93e-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="8f93e-106">Resource type</span></span></param>
        <param name="properties"><span data-ttu-id="8f93e-107">Die Eigenschaften, die mit einer Eingabe zugewiesen sind.</span><span class="sxs-lookup"><span data-stu-id="8f93e-107">The properties that are associated with an input.</span></span> <span data-ttu-id="8f93e-108">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8f93e-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <summary>
            <span data-ttu-id="8f93e-109">Initialisiert eine neue Instanz der Eingabe-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8f93e-109">Initializes a new instance of the Input class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.Input.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As InputProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.Input.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.InputProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8f93e-110">Ruft ab oder legt die Eigenschaften, die mit einer Eingabe zugewiesen sind.</span><span class="sxs-lookup"><span data-stu-id="8f93e-110">Gets or sets the properties that are associated with an input.</span></span>
            <span data-ttu-id="8f93e-111">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8f93e-111">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>