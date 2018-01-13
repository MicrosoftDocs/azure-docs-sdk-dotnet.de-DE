<Type Name="ImageStorageProfile" FullName="Microsoft.Azure.Management.Compute.Models.ImageStorageProfile">
  <TypeSignature Language="C#" Value="public class ImageStorageProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageStorageProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageStorageProfile" />
  <TypeSignature Language="F#" Value="type ImageStorageProfile = class" />
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
            Beschreibt ein Speicherprofil an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageStorageProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.#ctor" />
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
            Initialisiert eine neue Instanz der ImageStorageProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageStorageProfile (Microsoft.Azure.Management.Compute.Models.ImageOSDisk osDisk, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; dataDisks = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.ImageOSDisk osDisk, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; dataDisks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ImageOSDisk,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.ImageDataDisk})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osDisk As ImageOSDisk, Optional dataDisks As IList(Of ImageDataDisk) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageStorageProfile : Microsoft.Azure.Management.Compute.Models.ImageOSDisk * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ImageStorageProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ImageStorageProfile (osDisk, dataDisks)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osDisk" Type="Microsoft.Azure.Management.Compute.Models.ImageOSDisk" />
        <Parameter Name="dataDisks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt;" />
      </Parameters>
      <Docs>
        <param name="osDisk">Gibt Informationen zu den Betriebssystem-Datenträger, die von der virtuellen Maschine verwendet. &lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</param>
        <param name="dataDisks">Gibt die Parameter, die zum Hinzufügen eines Datenträgers an einen virtuellen Computer verwendet werden. &lt;Brasilien&gt;&lt;Br&gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</param>
        <summary>
            Initialisiert eine neue Instanz der ImageStorageProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As IList(Of ImageDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.ImageDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Parameter, die zum Hinzufügen eines Datenträgers an einen virtuellen Computer verwendet werden. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ImageOSDisk OsDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ImageOSDisk OsDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.OsDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property OsDisk As ImageOSDisk" />
      <MemberSignature Language="F#" Value="member this.OsDisk : Microsoft.Azure.Management.Compute.Models.ImageOSDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.OsDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ImageOSDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Informationen zu den Betriebssystem-Datenträger, die von der virtuellen Maschine verwendet. &amp;Lt; Br&amp;Gt;&amp; Lt; Br&amp;Gt; Weitere Informationen zu Datenträgern finden Sie unter [zu Datenträgern und virtuellen Festplatten für virtuelle Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-about-disks-vhds?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageStorageProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageStorageProfile.Validate " />
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>