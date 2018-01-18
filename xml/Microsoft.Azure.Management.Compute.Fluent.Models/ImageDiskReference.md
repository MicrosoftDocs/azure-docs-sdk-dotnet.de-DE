<Type Name="ImageDiskReference" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference">
  <TypeSignature Language="C#" Value="public class ImageDiskReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageDiskReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageDiskReference" />
  <TypeSignature Language="F#" Value="type ImageDiskReference = class" />
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
            <span data-ttu-id="e23f2-101">Zum Erstellen des Datenträgers Quellbilds.</span><span class="sxs-lookup"><span data-stu-id="e23f2-101">The source image used for creating the disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDiskReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e23f2-102">Initialisiert eine neue Instanz der ImageDiskReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e23f2-102">Initializes a new instance of the ImageDiskReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDiskReference (string id, Nullable&lt;int&gt; lun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;int32&gt; lun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional lun As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference (id, lun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="lun" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e23f2-103">Ein relativer Uri ist eine Plattform Imgage Repository oder Benutzer Bildverweis enthält.</span><span class="sxs-lookup"><span data-stu-id="e23f2-103">A relative uri containing either a Platform Imgage Repository or user image reference.</span></span></param>
        <param name="lun"><span data-ttu-id="e23f2-104">Wenn der Datenträger von Datenträger ein Image erstellt wird, ist dies ein Index, der die Datenträger für Daten in das zu verwendende Bild angibt.</span><span class="sxs-lookup"><span data-stu-id="e23f2-104">If the disk is created from an image's data disk, this is an index that indicates which of the data disks in the image to use.</span></span> <span data-ttu-id="e23f2-105">Für Betriebssystem-Datenträgern ist dieses Feld null.</span><span class="sxs-lookup"><span data-stu-id="e23f2-105">For OS disks, this field is null.</span></span></param>
        <summary>
            <span data-ttu-id="e23f2-106">Initialisiert eine neue Instanz der ImageDiskReference-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e23f2-106">Initializes a new instance of the ImageDiskReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e23f2-107">Ermittelt oder definiert einen relativen Uri handelt, die eine Plattform Imgage Repository oder Benutzer Bildverweis enthält.</span><span class="sxs-lookup"><span data-stu-id="e23f2-107">Gets or sets a relative uri containing either a Platform Imgage Repository or user image reference.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Lun : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e23f2-108">Ruft ab oder legt fest, ob die Datenträger aus dem Datenträger ein Image erstellt wird, ist dies ein Index, der die Datenträger für Daten in das zu verwendende Bild angibt.</span><span class="sxs-lookup"><span data-stu-id="e23f2-108">Gets or sets if the disk is created from an image's data disk, this is an index that indicates which of the data disks in the image to use.</span></span> <span data-ttu-id="e23f2-109">Für Betriebssystem-Datenträgern ist dieses Feld null.</span><span class="sxs-lookup"><span data-stu-id="e23f2-109">For OS disks, this field is null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.ImageDiskReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageDiskReference.Validate " />
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
            <span data-ttu-id="e23f2-110">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e23f2-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e23f2-111">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e23f2-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>