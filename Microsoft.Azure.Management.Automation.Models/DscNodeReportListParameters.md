<Type Name="DscNodeReportListParameters" FullName="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters">
  <TypeSignature Language="C#" Value="public class DscNodeReportListParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DscNodeReportListParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class DscNodeReportListParameters" />
  <TypeSignature Language="F#" Value="type DscNodeReportListParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Parameter für den Auftragsvorgang Liste angegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DscNodeReportListParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DscNodeReportListParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public string EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As String" />
      <MemberSignature Language="F#" Value="member this.EndTime : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Für das Ende sollte Zeitfilter der Wert eine Datetime-Zeichenfolge im UTC-Format gemäß ISO 8601 sein. Zum Beispiel: 2014-09-25T17:49:17.2252204Z
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public Guid NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As Guid" />
      <MemberSignature Language="F#" Value="member this.NodeId : Guid with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Ruft ab oder legt die Knoten-Id.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public string StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As String" />
      <MemberSignature Language="F#" Value="member this.StartTime : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Für den Beginn sollten Zeitfilter der Wert eine Datetime-Zeichenfolge im UTC-Format gemäß ISO 8601 sein. Zum Beispiel: 2014-09-25T17:49:17.2252204Z
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Ruft ab oder legt den Typ des Knotens Berichts fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>