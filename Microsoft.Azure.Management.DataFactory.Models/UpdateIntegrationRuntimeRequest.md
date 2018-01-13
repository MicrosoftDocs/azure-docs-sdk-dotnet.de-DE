<Type Name="UpdateIntegrationRuntimeRequest" FullName="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest">
  <TypeSignature Language="C#" Value="public class UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateIntegrationRuntimeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateIntegrationRuntimeRequest" />
  <TypeSignature Language="F#" Value="type UpdateIntegrationRuntimeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Aktualisieren Sie die Integration Common Language Runtime-Anforderung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der UpdateIntegrationRuntimeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeRequest (string autoUpdate = null, string updateDelayOffset = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string autoUpdate, string updateDelayOffset) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional autoUpdate As String = null, Optional updateDelayOffset As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest : string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest" Usage="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest (autoUpdate, updateDelayOffset)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoUpdate" Type="System.String" />
        <Parameter Name="updateDelayOffset" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="autoUpdate">Aktiviert oder deaktiviert die automatische Update-Funktion der integrationslaufzeit selbst gehosteten. Finden Sie unter https://go.microsoft.com/fwlink/?linkid=854189. Folgende Werte sind möglich: "On", "deaktiviert"</param>
        <param name="updateDelayOffset">Die Zeit des Tages (in Stunden)-offset ist z. B. PT03H 3 Stunden. Automatische Aktualisierung der Integration der Common Language Runtime erfolgt auf diesem Zeitpunkt.</param>
        <summary>
            Initialisiert eine neue Instanz der UpdateIntegrationRuntimeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUpdate">
      <MemberSignature Language="C#" Value="public string AutoUpdate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoUpdate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.AutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoUpdate As String" />
      <MemberSignature Language="F#" Value="member this.AutoUpdate : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.AutoUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoUpdate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt aktiviert oder deaktiviert die automatische Update-Funktion von der integrationslaufzeit selbst gehosteten. Finden Sie unter https://go.microsoft.com/fwlink/?linkid=854189. Folgende Werte sind möglich: "On", "deaktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDelayOffset">
      <MemberSignature Language="C#" Value="public string UpdateDelayOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateDelayOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.UpdateDelayOffset" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateDelayOffset As String" />
      <MemberSignature Language="F#" Value="member this.UpdateDelayOffset : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeRequest.UpdateDelayOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updateDelayOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitoffset (in Stunden) des Tages, z. B. PT03H 3 Stunden ist. Automatische Aktualisierung der Integration der Common Language Runtime erfolgt auf diesem Zeitpunkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>