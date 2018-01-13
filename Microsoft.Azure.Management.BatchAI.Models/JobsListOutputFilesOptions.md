<Type Name="JobsListOutputFilesOptions" FullName="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions">
  <TypeSignature Language="C#" Value="public class JobsListOutputFilesOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobsListOutputFilesOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class JobsListOutputFilesOptions" />
  <TypeSignature Language="F#" Value="type JobsListOutputFilesOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Zusätzliche Parameter für ListOutputFiles-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobsListOutputFilesOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobsListOutputFilesOptions (string outputdirectoryid, Nullable&lt;int&gt; linkexpiryinminutes = null, Nullable&lt;int&gt; maxResults = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputdirectoryid, valuetype System.Nullable`1&lt;int32&gt; linkexpiryinminutes, valuetype System.Nullable`1&lt;int32&gt; maxResults) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (outputdirectoryid As String, Optional linkexpiryinminutes As Nullable(Of Integer) = null, Optional maxResults As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions (outputdirectoryid, linkexpiryinminutes, maxResults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputdirectoryid" Type="System.String" />
        <Parameter Name="linkexpiryinminutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="outputdirectoryid">ID des Auftrags Ausgabeverzeichnis.
            Dies ist die OutputDirectory--&gt;Id-Parameter, der vom Benutzer, während der Auftrag zu erstellen angegeben wird.</param>
        <param name="linkexpiryinminutes">Die Anzahl der Minuten nach denen Download-Link abläuft.</param>
        <param name="maxResults">Die maximale Anzahl von Elementen, die in der Antwort zurückgegeben. Es kann maximal 1000 Dateien zurückgegeben werden.</param>
        <summary>
            Initialisiert eine neue Instanz der JobsListOutputFilesOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Linkexpiryinminutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Linkexpiryinminutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Linkexpiryinminutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Linkexpiryinminutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Linkexpiryinminutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Linkexpiryinminutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Minuten nach denen Download-Link abläuft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxResults : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Elementen, die in der Antwort zurückgegeben.
            Es kann maximal 1000 Dateien zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputdirectoryid">
      <MemberSignature Language="C#" Value="public string Outputdirectoryid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Outputdirectoryid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputdirectoryid As String" />
      <MemberSignature Language="F#" Value="member this.Outputdirectoryid : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Outputdirectoryid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Ausgabeverzeichnis des Auftrags-Id fest. Dies ist die OutputDirectory--&amp;Gt; Id-Parameter, der vom Benutzer, während der Auftrag zu erstellen angegeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobsListOutputFilesOptions.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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