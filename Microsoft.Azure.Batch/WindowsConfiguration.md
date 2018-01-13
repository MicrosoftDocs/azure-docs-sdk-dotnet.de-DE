<Type Name="WindowsConfiguration" FullName="Microsoft.Azure.Batch.WindowsConfiguration">
  <TypeSignature Language="C#" Value="public class WindowsConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.WindowsConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsConfiguration" />
  <TypeSignature Language="F#" Value="type WindowsConfiguration = class&#xA;    interface ITransportObjectProvider&lt;WindowsConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="993df-101">Windows-betriebssystemeinstellungen an den virtuellen Computer angewendet wurde.</span><span class="sxs-lookup"><span data-stu-id="993df-101">Windows operating system settings to apply to the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsConfiguration (Nullable&lt;bool&gt; enableAutomaticUpdates = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enableAutomaticUpdates) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.WindowsConfiguration.#ctor(System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enableAutomaticUpdates As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.WindowsConfiguration : Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.WindowsConfiguration" Usage="new Microsoft.Azure.Batch.WindowsConfiguration enableAutomaticUpdates" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enableAutomaticUpdates" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="enableAutomaticUpdates"><span data-ttu-id="993df-102">Gibt an, ob automatische Updates auf dem virtuellen Computer aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="993df-102">Whether automatic updates are enabled on the virtual machine.</span></span> <span data-ttu-id="993df-103">Falls nicht angegeben, ist der Standardwert "true".</span><span class="sxs-lookup"><span data-stu-id="993df-103">If unspecified, the default value is true.</span></span></param>
        <summary>
            <span data-ttu-id="993df-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.WindowsConfiguration" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="993df-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.WindowsConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutomaticUpdates">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAutomaticUpdates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAutomaticUpdates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnableAutomaticUpdates As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAutomaticUpdates : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Batch.WindowsConfiguration.EnableAutomaticUpdates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="993df-105">Ruft ab, ob automatische Updates auf dem virtuellen Computer aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="993df-105">Gets whether automatic updates are enabled on the virtual machine.</span></span> <span data-ttu-id="993df-106">Falls nicht angegeben, ist der Standardwert "true".</span><span class="sxs-lookup"><span data-stu-id="993df-106">If unspecified, the default value is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>