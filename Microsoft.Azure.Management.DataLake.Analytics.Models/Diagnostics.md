<Type Name="Diagnostics" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics">
  <TypeSignature Language="C#" Value="public class Diagnostics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Diagnostics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics" />
  <TypeSignature Language="VB.NET" Value="Public Class Diagnostics" />
  <TypeSignature Language="F#" Value="type Diagnostics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e91f2-101">Diagnose Fehlerinformationen für fehlgeschlagene Aufträge.</span><span class="sxs-lookup"><span data-stu-id="e91f2-101">Error diagnostic information for failed jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-102">Initialisiert eine neue Instanz der Diagnose-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e91f2-102">Initializes a new instance of the Diagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Diagnostics (Nullable&lt;int&gt; columnNumber = null, Nullable&lt;int&gt; end = null, Nullable&lt;int&gt; lineNumber = null, string message = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity = null, Nullable&lt;int&gt; start = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; columnNumber, valuetype System.Nullable`1&lt;int32&gt; end, valuetype System.Nullable`1&lt;int32&gt; lineNumber, string message, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity, valuetype System.Nullable`1&lt;int32&gt; start) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional columnNumber As Nullable(Of Integer) = null, Optional end As Nullable(Of Integer) = null, Optional lineNumber As Nullable(Of Integer) = null, Optional message As String = null, Optional severity As Nullable(Of SeverityTypes) = null, Optional start As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics (columnNumber, end, lineNumber, message, severity, start)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="columnNumber" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="end" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="lineNumber" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" />
        <Parameter Name="start" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="columnNumber"><span data-ttu-id="e91f2-103">die Spalte, in dem der Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="e91f2-103">the column where the error occured.</span></span></param>
        <param name="end"><span data-ttu-id="e91f2-104">Der Endindex des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="e91f2-104">the ending index of the error.</span></span></param>
        <param name="lineNumber"><span data-ttu-id="e91f2-105">die Nummer der Zeile, der den Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="e91f2-105">the line number the error occured on.</span></span></param>
        <param name="message"><span data-ttu-id="e91f2-106">Die Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="e91f2-106">the error message.</span></span></param>
        <param name="severity"><span data-ttu-id="e91f2-107">Der Schweregrad des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="e91f2-107">the severity of the error.</span></span> <span data-ttu-id="e91f2-108">Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"</span><span class="sxs-lookup"><span data-stu-id="e91f2-108">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span></param>
        <param name="start"><span data-ttu-id="e91f2-109">Der Startindex des Fehlers.</span><span class="sxs-lookup"><span data-stu-id="e91f2-109">the starting index of the error.</span></span></param>
        <summary>
            <span data-ttu-id="e91f2-110">Initialisiert eine neue Instanz der Diagnose-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e91f2-110">Initializes a new instance of the Diagnostics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ColumnNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ColumnNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.ColumnNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ColumnNumber As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ColumnNumber : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.ColumnNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columnNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-111">Ruft die Spalte, in dem der Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="e91f2-111">Gets the column where the error occured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.End : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="end")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-112">Ruft den Endwert Index des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="e91f2-112">Gets the ending index of the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LineNumber">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LineNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LineNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.LineNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LineNumber As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LineNumber : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.LineNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lineNumber")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-113">Ruft die Nummer der Zeile, der den Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="e91f2-113">Gets the line number the error occured on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="e91f2-114">Ruft die Fehlermeldung ab.</span><span class="sxs-lookup"><span data-stu-id="e91f2-114">Gets the error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As Nullable(Of SeverityTypes)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-115">Ruft den Schweregrad des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="e91f2-115">Gets the severity of the error.</span></span> <span data-ttu-id="e91f2-116">Folgende Werte sind möglich: "Warnung", "Fehler", "Info", "SevereWarning", "Veraltet", "UserWarning"</span><span class="sxs-lookup"><span data-stu-id="e91f2-116">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Start : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.Diagnostics.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="start")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e91f2-117">Ruft den Startindex des Fehlers ab.</span><span class="sxs-lookup"><span data-stu-id="e91f2-117">Gets the starting index of the error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>