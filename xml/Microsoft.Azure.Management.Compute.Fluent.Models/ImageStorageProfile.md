<Type Name="ImageStorageProfile" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile">
  <TypeSignature Language="C#" Value="public class ImageStorageProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageStorageProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageStorageProfile" />
  <TypeSignature Language="F#" Value="type ImageStorageProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3ec16-101">Beschreibt ein Speicherprofil an.</span><span class="sxs-lookup"><span data-stu-id="3ec16-101">Describes a storage profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageStorageProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ec16-102">Initialisiert eine neue Instanz der ImageStorageProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ec16-102">Initializes a new instance of the ImageStorageProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageStorageProfile (Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk osDisk, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; dataDisks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk osDisk, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; dataDisks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osDisk As ImageOSDisk, Optional dataDisks As IList(Of ImageDataDisk) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile (osDisk, dataDisks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="osDisk"><span data-ttu-id="3ec16-103">Die Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="3ec16-103">The OS disk.</span></span></param>
        <param name="dataDisks"><span data-ttu-id="3ec16-104">Der Datenträger für Daten.</span><span class="sxs-lookup"><span data-stu-id="3ec16-104">The data disks.</span></span></param>
        <summary>
            <span data-ttu-id="3ec16-105">Initialisiert eine neue Instanz der ImageStorageProfile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3ec16-105">Initializes a new instance of the ImageStorageProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of ImageDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ImageDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ec16-106">Ruft ab oder legt die Datenträger.</span><span class="sxs-lookup"><span data-stu-id="3ec16-106">Gets or sets the data disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As ImageOSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageOSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3ec16-107">Ruft ab oder legt den Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="3ec16-107">Gets or sets the OS disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageStorageProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageStorageProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3ec16-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3ec16-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3ec16-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3ec16-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>