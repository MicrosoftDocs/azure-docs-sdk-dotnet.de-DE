<Type Name="CloudServiceConfiguration" FullName="Microsoft.Azure.Batch.CloudServiceConfiguration">
  <TypeSignature Language="C#" Value="public class CloudServiceConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudServiceConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudServiceConfiguration" />
  <TypeSignature Language="F#" Value="type CloudServiceConfiguration = class&#xA;    interface ITransportObjectProvider&lt;CloudServiceConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Die Konfiguration für die Serverknoten in einem Pool basierend auf der Azure Cloud Services-Plattform.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration (string osFamily, string targetOSVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string osFamily, string targetOSVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudServiceConfiguration.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osFamily As String, Optional targetOSVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.CloudServiceConfiguration : string * string -&gt; Microsoft.Azure.Batch.CloudServiceConfiguration" Usage="new Microsoft.Azure.Batch.CloudServiceConfiguration (osFamily, targetOSVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osFamily" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osFamily">Die Azure-Gastbetriebssystemfamilie, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll. Wenn kein Wert angegeben ist, wird standardmäßig der Batch-Dienst auf "" * ", die angibt, dass die neueste Version des Betriebssystems für die <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.OSFamily" />.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentOSVersion">
      <MemberSignature Language="C#" Value="public string CurrentOSVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.CurrentOSVersion : string" Usage="Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Azure-Gastbetriebssystem-Version, die derzeit auf den virtuellen Computern im Pool installiert. Dies unterscheidet sich möglicherweise von <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> Wenn der Poolstatus ist <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSFamily">
      <MemberSignature Language="C#" Value="public string OSFamily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSFamily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudServiceConfiguration.OSFamily" />
      <MemberSignature Language="VB.NET" Value="Public Property OSFamily As String" />
      <MemberSignature Language="F#" Value="member this.OSFamily : string with get, set" Usage="Microsoft.Azure.Batch.CloudServiceConfiguration.OSFamily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure-gastbetriebssystemfamilie auf den virtuellen Computern im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Weitere Informationen zu den Gast-BS-Familien finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetOSVersion">
      <MemberSignature Language="C#" Value="public string TargetOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetOSVersion : string with get, set" Usage="Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure-Gast-BS-Version auf den virtuellen Computern im Pool installiert werden. Wenn kein Wert angegeben ist, wird standardmäßig der Batch-Dienst auf "" * ", die angibt, dass die neueste Version des Betriebssystems für die <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.OSFamily" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>