<Type Name="OperationDefinition" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition">
  <TypeSignature Language="C#" Value="public class OperationDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationDefinition" />
  <TypeSignature Language="F#" Value="type OperationDefinition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1146-101">Die Definition eines Container-Registrierungs-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="d1146-101">The definition of a container registry operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1146-102">Initialisiert eine neue Instanz der OperationDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1146-102">Initializes a new instance of the OperationDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationDefinition (string name = null, Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition display = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition display) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional display As OperationDisplayDefinition = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition : string * Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition (name, display)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="display" Type="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d1146-103">Vorgangsname: {Anbieter} / {Resource} / {Operation}.</span><span class="sxs-lookup"><span data-stu-id="d1146-103">Operation name: {provider}/{resource}/{operation}.</span></span></param>
        <param name="display"><span data-ttu-id="d1146-104">Die Anzeigeinformationen für die Container-Registrierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="d1146-104">The display information for the container registry operation.</span></span></param>
        <summary>
            <span data-ttu-id="d1146-105">Initialisiert eine neue Instanz der OperationDefinition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1146-105">Initializes a new instance of the OperationDefinition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Display">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition Display { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition Display" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Display" />
      <MemberSignature Language="VB.NET" Value="Public Property Display As OperationDisplayDefinition" />
      <MemberSignature Language="F#" Value="member this.Display : Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Display" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="display")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.OperationDisplayDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1146-106">Ruft ab oder legt die Anzeigeinformationen für die Container-Registrierungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="d1146-106">Gets or sets the display information for the container registry operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.OperationDefinition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d1146-107">Ruft ab oder legt ihn fest Vorgangsname: {Anbieter} / {Resource} / {Operation}.</span><span class="sxs-lookup"><span data-stu-id="d1146-107">Gets or sets operation name: {provider}/{resource}/{operation}.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>