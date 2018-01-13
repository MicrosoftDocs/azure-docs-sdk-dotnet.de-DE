<Type Name="AvailableProviderOperationDisplay" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay">
  <TypeSignature Language="C#" Value="public class AvailableProviderOperationDisplay" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProviderOperationDisplay extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProviderOperationDisplay" />
  <TypeSignature Language="F#" Value="type AvailableProviderOperationDisplay = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält die lokalisierten Anzeigeinformationen für diese bestimmten Vorgang/Aktion an. Dieser Wert wird von mehreren Clients (a) benutzerdefinierten Rollendefinitionen für RBAC, (b) komplexe Abfragefilter für die Ereignis-Dienst und (c) Überwachung/Verlaufsdatensätze für Verwaltungsvorgänge verwendet werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AvailableProviderOperationDisplay-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProviderOperationDisplay (string provider = null, string resource = null, string operation = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string resource, string operation, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional resource As String = null, Optional operation As String = null, Optional description As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay : string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay (provider, resource, operation, description)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="provider">Die lokalisierte benutzerfreundliche Form der Name des Ressourcenanbieters - es wird erwartet, dass auch der Verleger/verantwortlich enthalten sind. Es Titelschreibweise verwenden und beginnen mit 'Microsoft' für den 1. Services von Drittanbietern.</param>
        <param name="resource">Die lokalisierte benutzerfreundliche Form des Typs der Ressource im Zusammenhang mit dieser Aktion/Operation - sollte es die öffentliche Dokumentation für den Ressourcenanbieter übereinstimmen. Es sollten Titel Groß-/Kleinschreibung verwenden.
            - Beispiele finden Sie im Abschnitt "Name".</param>
        <param name="operation">Der lokalisierte Anzeigenamen für den Vorgang, da es dem Benutzer angezeigt werden soll. Dies sollte (um die Dropdownfelder zu groß) präzise aber deaktivieren (d. h. selbstdokumentierend) sein. Es sollen die Entitätsressource/für die er gilt Titelschreibweise verwenden und eingeschlossen werden.</param>
        <param name="description">Die lokalisierte Beschreibung für den Vorgang, da es dem Benutzer angezeigt werden soll. Sollten Sie umfassend sein noch präzise - wird in QuickInfos verwendet und detaillierte Ansichten.</param>
        <summary>
            Initialisiert eine neue Instanz der AvailableProviderOperationDisplay-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die lokalisierte Beschreibung für den Vorgang, wie es dem Benutzer angezeigt werden sollen. Sollten Sie umfassend sein noch präzise - wird in QuickInfos verwendet und detaillierte Ansichten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den lokalisierten Anzeigenamen für den Vorgang, wie es dem Benutzer angezeigt werden sollen. Dies sollte (um die Dropdownfelder zu groß) präzise aber deaktivieren (d. h. selbstdokumentierend) sein. Es sollen die Entitätsressource/für die er gilt Titelschreibweise verwenden und eingeschlossen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den lokalisierte Anzeigename Form der Name des Ressourcenanbieters - es wird erwartet, dass auch der Verleger/verantwortlich enthalten sind. Es Titelschreibweise verwenden und beginnen mit 'Microsoft' für den 1. Services von Drittanbietern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resource">
      <MemberSignature Language="C#" Value="public string Resource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberSignature Language="VB.NET" Value="Public Property Resource As String" />
      <MemberSignature Language="F#" Value="member this.Resource : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.AvailableProviderOperationDisplay.Resource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den lokalisierte Anzeigename Formular des Ressourcentyps mit dieser Aktion/Vorgang - verknüpft sollte es die öffentliche Dokumentation für den Ressourcenanbieter übereinstimmen. Es sollten Titel Groß-/Kleinschreibung verwenden.
            - Beispiele finden Sie im Abschnitt "Name".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>