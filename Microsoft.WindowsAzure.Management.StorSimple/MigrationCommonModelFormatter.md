<Type Name="MigrationCommonModelFormatter" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter">
  <TypeSignature Language="C#" Value="public class MigrationCommonModelFormatter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationCommonModelFormatter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationCommonModelFormatter" />
  <TypeSignature Language="F#" Value="type MigrationCommonModelFormatter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationCommonModelFormatter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcatStringList">
      <MemberSignature Language="C#" Value="public string ConcatStringList (System.Collections.Generic.List&lt;string&gt; stringList, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string ConcatStringList(class System.Collections.Generic.List`1&lt;string&gt; stringList, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.ConcatStringList(System.Collections.Generic.List{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ConcatStringList (stringList As List(Of String), Optional delimiter As String = null) As String" />
      <MemberSignature Language="F#" Value="member this.ConcatStringList : System.Collections.Generic.List&lt;string&gt; * string -&gt; string" Usage="migrationCommonModelFormatter.ConcatStringList (stringList, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stringList" Type="System.Collections.Generic.List&lt;System.String&gt;" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="stringList">Liste der Zeichenfolge verketten</param>
        <param name="delimiter">Trennzeichen BW einzelne Zeichenfolgen</param>
        <summary>
            Concats alle String angegebenen Liste getrennt durch das angegebene Trennzeichen
            </summary>
        <returns>einzelne Zeichenfolge, die durch Verketten von Zeichenfolgen aus gebildet</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTimeSpan">
      <MemberSignature Language="C#" Value="public string FormatTimeSpan (TimeSpan span);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string FormatTimeSpan(valuetype System.TimeSpan span) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.FormatTimeSpan(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function FormatTimeSpan (span As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="member this.FormatTimeSpan : TimeSpan -&gt; string" Usage="migrationCommonModelFormatter.FormatTimeSpan span" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="span" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="span">Zeitspanne angezeigt</param>
        <summary>
            Formatieren Sie den Zeitraum
            </summary>
        <returns>Zeitspanne im Zeichenfolgenformat</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResultMessage">
      <MemberSignature Language="C#" Value="public string GetResultMessage (string successMsg, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetResultMessage(string successMsg, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.GetResultMessage(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetResultMessage (successMsg As String, status As MigrationJobStatus) As String" />
      <MemberSignature Language="F#" Value="member this.GetResultMessage : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus -&gt; string" Usage="migrationCommonModelFormatter.GetResultMessage (successMsg, status)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="successMsg" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" />
      </Parameters>
      <Docs>
        <param name="successMsg">To be added.</param>
        <param name="status">Migration des Auftragsstatus</param>
        <summary>
            Ruft bestätigen Migration Erfolgsmeldung, die mit Fehlerzeichenfolge, die vom Dienst abgerufen werden
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HcsMessageInfoToString">
      <MemberSignature Language="C#" Value="public string HcsMessageInfoToString (Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo msgInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string HcsMessageInfoToString(class Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo msgInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.HcsMessageInfoToString(Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function HcsMessageInfoToString (msgInfo As HcsMessageInfo) As String" />
      <MemberSignature Language="F#" Value="member this.HcsMessageInfoToString : Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo -&gt; string" Usage="migrationCommonModelFormatter.HcsMessageInfoToString msgInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="msgInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.HcsMessageInfo" />
      </Parameters>
      <Docs>
        <param name="msgInfo">msg Info o/p</param>
        <summary>
            Konvertiert HcsMessageInfo in die gewünschte Ausgabe der Zeichenfolge
            </summary>
        <returns>Anzeigezeichenfolge</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntendAndConCat">
      <MemberSignature Language="C#" Value="public string IntendAndConCat (string prefix, object suffix, int maxLength = -1, string delimiter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string IntendAndConCat(string prefix, object suffix, int32 maxLength, string delimiter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationCommonModelFormatter.IntendAndConCat(System.String,System.Object,System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IntendAndConCat (prefix As String, suffix As Object, Optional maxLength As Integer = -1, Optional delimiter As String = null) As String" />
      <MemberSignature Language="F#" Value="member this.IntendAndConCat : string * obj * int * string -&gt; string" Usage="migrationCommonModelFormatter.IntendAndConCat (prefix, suffix, maxLength, delimiter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="suffix" Type="System.Object" />
        <Parameter Name="maxLength" Type="System.Int32" />
        <Parameter Name="delimiter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="prefix">Name des Objekts suffix</param>
        <param name="suffix">Objekt, das in eine Zeichenfolge konvertiert werden soll</param>
        <param name="maxLength">MaxLength, welches Präfix Indentented werden sollen</param>
        <param name="delimiter">als Trennzeichen zwischen Präfix und das Suffix Objekt</param>
        <summary>
            Die API wird verwendet, Concats die Präfix- und String-Darstellung des Objekts angegeben wird, getrennt durch Trennzeichen mit den richtigen Einzug BW Zeichenfolgen
            </summary>
        <returns>Zeichenfolge, die durch Verketten von Präfix und Suffix gebildet</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>