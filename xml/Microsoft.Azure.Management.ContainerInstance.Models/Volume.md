<Type Name="Volume" FullName="Microsoft.Azure.Management.ContainerInstance.Models.Volume">
  <TypeSignature Language="C#" Value="public class Volume" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Volume extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.Volume" />
  <TypeSignature Language="VB.NET" Value="Public Class Volume" />
  <TypeSignature Language="F#" Value="type Volume = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60a0f-101">Die Eigenschaften des Volumes.</span><span class="sxs-lookup"><span data-stu-id="60a0f-101">The properties of the volume.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Volume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60a0f-102">Initialisiert eine neue Instanz der Volume-Klasse.</span><span class="sxs-lookup"><span data-stu-id="60a0f-102">Initializes a new instance of the Volume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume (string name, Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume azureFile = null, object emptyDir = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume azureFile, object emptyDir) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Volume.#ctor(System.String,Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional azureFile As AzureFileVolume = null, Optional emptyDir As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.Volume : string * Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume * obj -&gt; Microsoft.Azure.Management.ContainerInstance.Models.Volume" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.Volume (name, azureFile, emptyDir)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="azureFile" Type="Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume" />
        <Parameter Name="emptyDir" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="60a0f-103">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="60a0f-103">The name of the volume.</span></span></param>
        <param name="azureFile"><span data-ttu-id="60a0f-104">Der Name des Azure-Dateidienst Volumes.</span><span class="sxs-lookup"><span data-stu-id="60a0f-104">The name of the Azure File volume.</span></span></param>
        <param name="emptyDir"><span data-ttu-id="60a0f-105">Das Volume leeren Verzeichnisses.</span><span class="sxs-lookup"><span data-stu-id="60a0f-105">The empty directory volume.</span></span></param>
        <summary>
            <span data-ttu-id="60a0f-106">Initialisiert eine neue Instanz der Volume-Klasse.</span><span class="sxs-lookup"><span data-stu-id="60a0f-106">Initializes a new instance of the Volume class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume AzureFile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume AzureFile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Volume.AzureFile" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureFile As AzureFileVolume" />
      <MemberSignature Language="F#" Value="member this.AzureFile : Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Volume.AzureFile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureFile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerInstance.Models.AzureFileVolume</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60a0f-107">Ruft ab oder legt den Namen des Azure-Dateidienst Volumes fest.</span><span class="sxs-lookup"><span data-stu-id="60a0f-107">Gets or sets the name of the Azure File volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EmptyDir">
      <MemberSignature Language="C#" Value="public object EmptyDir { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EmptyDir" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Volume.EmptyDir" />
      <MemberSignature Language="VB.NET" Value="Public Property EmptyDir As Object" />
      <MemberSignature Language="F#" Value="member this.EmptyDir : obj with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Volume.EmptyDir" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="emptyDir")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60a0f-108">Ermittelt oder definiert das leere Verzeichnis Volume.</span><span class="sxs-lookup"><span data-stu-id="60a0f-108">Gets or sets the empty directory volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.Volume.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.Volume.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="60a0f-109">Ruft ab oder legt den Namen des Volumes.</span><span class="sxs-lookup"><span data-stu-id="60a0f-109">Gets or sets the name of the volume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.Volume.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="volume.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60a0f-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="60a0f-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60a0f-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="60a0f-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>