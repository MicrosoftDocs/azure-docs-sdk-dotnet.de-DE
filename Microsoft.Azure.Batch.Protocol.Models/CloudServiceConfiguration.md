<Type Name="CloudServiceConfiguration" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration">
  <TypeSignature Language="C#" Value="public class CloudServiceConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudServiceConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudServiceConfiguration" />
  <TypeSignature Language="F#" Value="type CloudServiceConfiguration = class" />
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
            Die Konfiguration für Knoten in einem Pool basierend auf der Azure Cloud Services-Plattform.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloudServiceConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration (string osFamily, string targetOSVersion = null, string currentOSVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string osFamily, string targetOSVersion, string currentOSVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osFamily As String, Optional targetOSVersion As String = null, Optional currentOSVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration (osFamily, targetOSVersion, currentOSVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osFamily" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="currentOSVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osFamily">Die Azure-Gastbetriebssystemfamilie, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="targetOSVersion">Die Azure-Gastbetriebssystemversion, die auf den virtuellen Computern im Pool installiert werden soll.</param>
        <param name="currentOSVersion">Die Azure Guest OS derzeit installierte Version auf den virtuellen Computern im Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der CloudServiceConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentOSVersion">
      <MemberSignature Language="C#" Value="public string CurrentOSVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.CurrentOSVersion : string" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Azure-Gastbetriebssystemversion, die derzeit auf den virtuellen Computern im Pool installiert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies kann von TargetOSVersion abweichen, wenn der den Poolstatus aktualisieren. In diesem Fall möglicherweise einige virtuelle Maschinen auf dem TargetOSVersion und einigen kann es sich auf die CurrentOSVersion während des Upgrades. Sobald alle virtuellen Computer aktualisiert haben, wird CurrentOSVersion aktualisiert, um dem TargetOSVersion identisch sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsFamily">
      <MemberSignature Language="C#" Value="public string OsFamily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsFamily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.OsFamily" />
      <MemberSignature Language="VB.NET" Value="Public Property OsFamily As String" />
      <MemberSignature Language="F#" Value="member this.OsFamily : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.OsFamily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osFamily")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure-gastbetriebssystemfamilie auf den virtuellen Computern im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mögliche Werte sind: 2 - BS-Familie 2, Windows Server 2008 R2 SP1 entspricht. 3 - Gastbetriebssystemfamilie 3, Windows Server 2012 entspricht. 4
            - Gastbetriebssystemfamilie 4, Windows Server 2012 R2 entspricht. 5 – Betriebssystem-Familie 5, gleichbedeutend mit Windows Server 2016. Weitere Informationen finden Sie in der Azure-Gastbetriebssystemversionen (https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/#releases).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetOSVersion">
      <MemberSignature Language="C#" Value="public string TargetOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetOSVersion : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure-Gast-BS-Version auf den virtuellen Computern im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist * gibt die aktuelle Betriebssystemversion für die angegebene Betriebssystemfamilie an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudServiceConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudServiceConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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