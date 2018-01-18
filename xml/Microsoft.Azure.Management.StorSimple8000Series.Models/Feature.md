<Type Name="Feature" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Feature">
  <TypeSignature Language="C#" Value="public class Feature" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Feature extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature" />
  <TypeSignature Language="VB.NET" Value="Public Class Feature" />
  <TypeSignature Language="F#" Value="type Feature = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a6d6c-101">Die Funktion.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-101">The feature.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Feature ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6d6c-102">Initialisiert eine neue Instanz der Feature-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-102">Initializes a new instance of the Feature class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Feature (string name, Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, status As FeatureSupportStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Feature : string * Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Feature" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Feature (name, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a6d6c-103">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-103">The name of the feature.</span></span></param>
        <param name="status"><span data-ttu-id="a6d6c-104">Der Funktionsstatus Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-104">The feature support status.</span></span> <span data-ttu-id="a6d6c-105">Folgende Werte sind möglich: "Nicht verfügbar", "UnsupportedDeviceVersion", "Unterstützt"</span><span class="sxs-lookup"><span data-stu-id="a6d6c-105">Possible values include: 'NotAvailable', 'UnsupportedDeviceVersion', 'Supported'</span></span></param>
        <summary>
            <span data-ttu-id="a6d6c-106">Initialisiert eine neue Instanz der Feature-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-106">Initializes a new instance of the Feature class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="a6d6c-107">Ruft ab oder legt den Namen der Funktion fest.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-107">Gets or sets the name of the feature.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As FeatureSupportStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureSupportStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6d6c-108">Ruft ab oder legt den Status der Feature-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-108">Gets or sets the feature support status.</span></span> <span data-ttu-id="a6d6c-109">Folgende Werte sind möglich: "Nicht verfügbar", "UnsupportedDeviceVersion", "Unterstützt"</span><span class="sxs-lookup"><span data-stu-id="a6d6c-109">Possible values include: 'NotAvailable', 'UnsupportedDeviceVersion', 'Supported'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Feature.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="feature.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6d6c-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a6d6c-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a6d6c-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a6d6c-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>