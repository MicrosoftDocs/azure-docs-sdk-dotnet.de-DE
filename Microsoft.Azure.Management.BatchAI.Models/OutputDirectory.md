<Type Name="OutputDirectory" FullName="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory">
  <TypeSignature Language="C#" Value="public class OutputDirectory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputDirectory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputDirectory" />
  <TypeSignature Language="F#" Value="type OutputDirectory = class" />
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
            Ausgabeverzeichnis für den Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse OutputDirectory an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputDirectory (string id, string pathPrefix, string pathSuffix = null, string type = null, Nullable&lt;bool&gt; createNew = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string pathPrefix, string pathSuffix, string type, valuetype System.Nullable`1&lt;bool&gt; createNew) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, pathPrefix As String, Optional pathSuffix As String = null, Optional type As String = null, Optional createNew As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory : string * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.OutputDirectory" Usage="new Microsoft.Azure.Management.BatchAI.Models.OutputDirectory (id, pathPrefix, pathSuffix, type, createNew)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="pathSuffix" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="createNew" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Der Name für das Ausgabeverzeichnis.</param>
        <param name="pathPrefix">Der Präfix-Pfad, in dem das Ausgabeverzeichnis erstellt werden soll.</param>
        <param name="pathSuffix">Das Suffix-Pfad, in dem das Ausgabeverzeichnis erstellt werden soll.</param>
        <param name="type">Eine Enumeration, die den Typ des Auftrags Ausgabeverzeichnis angibt.</param>
        <param name="createNew">True, um das neue Verzeichnis zu erstellen.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse OutputDirectory an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNew">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CreateNew { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CreateNew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNew As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CreateNew : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.CreateNew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createNew")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest "true", neues Verzeichnis erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist true. Wenn "false", kann das Verzeichnis nicht erstellt und kann Verzeichnispfad, der den Benutzer angibt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen für das Ausgabeverzeichnis.
            </summary>
        <value>To be added.</value>
        <remarks>
            Es wird für den Auftrag als Umgebungsvariable unter AZ_BATCHAI_OUTPUT_id verfügbar sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPrefix">
      <MemberSignature Language="C#" Value="public string PathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Präfix-Pfad, in dem das Ausgabeverzeichnis erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Hinweis: Dies ist ein absoluter Pfad voranstellen. Beispiel:
            $AZ_BATCHAI_MOUNT_ROOT/MyNFS/MyLogs.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PathSuffix">
      <MemberSignature Language="C#" Value="public string PathSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property PathSuffix As String" />
      <MemberSignature Language="F#" Value="member this.PathSuffix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.PathSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pathSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Suffix Pfad, in dem das Ausgabeverzeichnis erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das Suffix-Pfad, in dem das Ausgabeverzeichnis erstellt werden soll.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Enumeration, die den Typ des Auftrags Ausgabeverzeichnis angibt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Standardwert ist benutzerdefiniert. Die möglichen Werte sind Modell, Protokolle, Zusammenfassung und Benutzerdefiniert. Benutzer können mehrere Enumerationen für ein einzelnes Verzeichnis verwenden. Beispiel: OutPutType = "Modell, Protokolle, Summary". Folgende Werte sind möglich: "Modell", "Protokolle", "Zusammenfassung", "Custom"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.OutputDirectory.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputDirectory.Validate " />
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