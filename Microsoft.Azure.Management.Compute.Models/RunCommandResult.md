<Type Name="RunCommandResult" FullName="Microsoft.Azure.Management.Compute.Models.RunCommandResult">
  <TypeSignature Language="C#" Value="public class RunCommandResult : Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RunCommandResult extends Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RunCommandResult" />
  <TypeSignature Language="VB.NET" Value="Public Class RunCommandResult&#xA;Inherits OperationStatusResponse" />
  <TypeSignature Language="F#" Value="type RunCommandResult = class&#xA;    inherit OperationStatusResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Führen Sie Befehlsantwort-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandResult.#ctor" />
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
            Initialisiert eine neue Instanz der RunCommandResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RunCommandResult (string name = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Management.Compute.Models.ApiError error = null, object output = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Management.Compute.Models.ApiError error, object output) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RunCommandResult.#ctor(System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.Compute.Models.ApiError,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional error As ApiError = null, Optional output As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RunCommandResult : string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Compute.Models.ApiError * obj -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandResult" Usage="new Microsoft.Azure.Management.Compute.Models.RunCommandResult (name, status, startTime, endTime, error, output)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.Compute.Models.ApiError" />
        <Parameter Name="output" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">Vorgangs-ID</param>
        <param name="status">Vorgangsstatus</param>
        <param name="startTime">Startzeit des Vorgangs</param>
        <param name="endTime">Die Endzeit des Vorgangs</param>
        <param name="error">API-Fehler</param>
        <param name="output">Ausgabe Vorgangsdaten (raw JSON)</param>
        <summary>
            Initialisiert eine neue Instanz der RunCommandResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Output">
      <MemberSignature Language="C#" Value="public object Output { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Output" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RunCommandResult.Output" />
      <MemberSignature Language="VB.NET" Value="Public Property Output As Object" />
      <MemberSignature Language="F#" Value="member this.Output : obj with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RunCommandResult.Output" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.output")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Ausgabe Vorgangsdaten (raw JSON)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>