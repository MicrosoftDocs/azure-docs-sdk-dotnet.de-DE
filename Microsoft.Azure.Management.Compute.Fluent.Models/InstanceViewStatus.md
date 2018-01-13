<Type Name="InstanceViewStatus" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus">
  <TypeSignature Language="C#" Value="public class InstanceViewStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit InstanceViewStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class InstanceViewStatus" />
  <TypeSignature Language="F#" Value="type InstanceViewStatus = class" />
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
            Status der Instanz anzeigen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstanceViewStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der InstanceViewStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InstanceViewStatus (string code = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; level = null, string displayStatus = null, string message = null, Nullable&lt;DateTime&gt; time = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string code, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; level, string displayStatus, string message, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; time) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.#ctor(System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes},System.String,System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional code As String = null, Optional level As Nullable(Of StatusLevelTypes) = null, Optional displayStatus As String = null, Optional message As String = null, Optional time As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus : string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; * string * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus (code, level, displayStatus, message, time)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt;" />
        <Parameter Name="displayStatus" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="time" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="code">Der Statuscode.</param>
        <param name="level">Der Code, Ebene. Folgende Werte sind möglich: "Info", "Warnung", "Fehler"</param>
        <param name="displayStatus">Die kurzen lokalisierbare Bezeichnung für den Status.</param>
        <param name="message">Die detaillierte Statusmeldung, einschließlich Warnungen und Fehlermeldungen.</param>
        <param name="time">Die Zeit des Status.</param>
        <summary>
            Initialisiert eine neue Instanz der InstanceViewStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="code")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Statuscode.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayStatus">
      <MemberSignature Language="C#" Value="public string DisplayStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.DisplayStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayStatus As String" />
      <MemberSignature Language="F#" Value="member this.DisplayStatus : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.DisplayStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die kurze lokalisierbare Bezeichnung für den Status.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of StatusLevelTypes)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.StatusLevelTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Ebenen Code. Folgende Werte sind möglich: "Info", "Warnung", "Fehler"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die detaillierte Statusmeldung, einschließlich Warnungen und Fehlermeldungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Time">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Time { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Time" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Time" />
      <MemberSignature Language="VB.NET" Value="Public Property Time As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Time : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus.Time" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit des Status.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>