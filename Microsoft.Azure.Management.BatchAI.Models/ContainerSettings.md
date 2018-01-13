<Type Name="ContainerSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ContainerSettings">
  <TypeSignature Language="C#" Value="public class ContainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ContainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerSettings" />
  <TypeSignature Language="F#" Value="type ContainerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b26a7-101">Einstellungen für den Container heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="b26a7-101">Settings for the container to be downloaded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ContainerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b26a7-102">Initialisiert eine neue Instanz der ContainerSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b26a7-102">Initializes a new instance of the ContainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerSettings (Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry imageSourceRegistry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry imageSourceRegistry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ContainerSettings.#ctor(Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ContainerSettings : Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry -&gt; Microsoft.Azure.Management.BatchAI.Models.ContainerSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ContainerSettings imageSourceRegistry" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageSourceRegistry" Type="Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry" />
      </Parameters>
      <Docs>
        <param name="imageSourceRegistry"><span data-ttu-id="b26a7-103">Die Registrierung zum Herunterladen des Containers aus.</span><span class="sxs-lookup"><span data-stu-id="b26a7-103">Registry to download the container from.</span></span></param>
        <summary>
            <span data-ttu-id="b26a7-104">Initialisiert eine neue Instanz der ContainerSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b26a7-104">Initializes a new instance of the ContainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageSourceRegistry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry ImageSourceRegistry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry ImageSourceRegistry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ContainerSettings.ImageSourceRegistry" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageSourceRegistry As ImageSourceRegistry" />
      <MemberSignature Language="F#" Value="member this.ImageSourceRegistry : Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ContainerSettings.ImageSourceRegistry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageSourceRegistry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ImageSourceRegistry</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b26a7-105">Abrufen oder Festlegen der Registrierung zum Herunterladen des Containers aus.</span><span class="sxs-lookup"><span data-stu-id="b26a7-105">Gets or sets registry to download the container from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ContainerSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b26a7-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b26a7-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b26a7-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b26a7-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>