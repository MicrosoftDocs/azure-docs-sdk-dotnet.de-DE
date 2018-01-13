<Type Name="ApplicationHealthPolicy" FullName="System.Fabric.Health.ApplicationHealthPolicy">
  <TypeSignature Language="C#" Value="public class ApplicationHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationHealthPolicy" />
  <TypeSignature Language="F#" Value="type ApplicationHealthPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Definiert eine Integritätsrichtlinie verwendet, um den Zustand des Service Fabric-Anwendung oder eines seiner untergeordneten Entitäten auszuwerten.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />-Klasse.</para>
        </summary>
        <remarks>Der Standardwert einer anwendungsintegritäts-Richtlinie tolerieren keine Fehler oder Warnungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsiderWarningAsError">
      <MemberSignature Language="C#" Value="public bool ConsiderWarningAsError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsiderWarningAsError" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsiderWarningAsError As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsiderWarningAsError : bool with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.ConsiderWarningAsError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt einen <see cref="T:System.Boolean" /> , der bestimmt, ob Berichte mit Status "Warnung" mit den gleichen Schweregrad als Fehler behandelt werden sollen.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> Wenn Berichte mit Status "Warnung" als Fehler behandelt werden sollen <languageKeyword>"false"</languageKeyword> Wenn Warnungen nicht als Fehler behandelt werden soll.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultServiceTypeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceTypeHealthPolicy DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultServiceTypeHealthPolicy As ServiceTypeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.DefaultServiceTypeHealthPolicy : System.Fabric.Health.ServiceTypeHealthPolicy with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceTypeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen oder festlegen die Integritätsrichtlinie, die standardmäßig verwendet wird, um den Zustand eines Diensttyps auszuwerten.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> verwendet, um die Integrität des Diensts-Typ zu ermitteln, ob keine dienstrichtlinie für den Typ definiert ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyDeployedApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyDeployedApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyDeployedApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyDeployedApplications : byte with get, set" Usage="System.Fabric.Health.ApplicationHealthPolicy.MaxPercentUnhealthyDeployedApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den maximalen zulässigen Prozentsatz an fehlerhaften bereitgestellten Anwendungen.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter bereitgestellte Anwendungen. Zulässige Werte sind <see cref="T:System.Byte" /> Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz stellt den zulässigen maximalen Prozentsatz der bereitgestellten Anwendungen, die fehlerhaft sein kann, bevor die Anwendung bei Fehler betrachtet wird. Dies wird berechnet durch Dividieren der Anzahl der fehlerhaften bereitgestellten Anwendungen über die Anzahl der Knoten, die die Anwendungen derzeit auf dem Cluster bereitgestellt werden.
            Die Berechnung wird aufgerundet, um einen Fehler auf einer kleinen Anzahl von Knoten zu tolerieren. Standardprozentsatz : null.
            </para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class System.Fabric.Health.ServiceTypeHealthPolicy&gt; ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeHealthPolicyMap As IDictionary(Of String, ServiceTypeHealthPolicy)" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeHealthPolicyMap : System.Collections.Generic.IDictionary&lt;string, System.Fabric.Health.ServiceTypeHealthPolicy&gt;" Usage="System.Fabric.Health.ApplicationHealthPolicy.ServiceTypeHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Fabric.Health.ServiceTypeHealthPolicy&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Zuordnung mit <see cref="T:System.Fabric.Health.ServiceTypeHealthPolicy" /> pro Diensttypname. </para>
        </summary>
        <value>
          <para>Die Zuordnung mit einer Dienst-Typ-Integritätsrichtlinie pro Diensttypname.</para>
        </value>
        <remarks>
          <para>Die Einträge in der Zuordnung ersetzen Sie die Standard-Dienst Typ Integritätsrichtlinie für jeden angegebenen Diensttyp.
            Beispielsweise können in einer Anwendung, die einen Diensttyp für zustandslose Gateway und einen Diensttyp für zustandsbehaftete Modul enthält, die Integritätsrichtlinien für die Zustandslose und zustandsbehaftete Dienste unterschiedlich konfiguriert sein.
            Mit der Richtlinie pro Diensttyp besteht eine detailliertere Kontrolle über die Integrität des Diensts zur Verfügung.
            </para>
          <para>Wenn keine Richtlinie für einen Dienstnamen Typ angegeben ist die <see cref="P:System.Fabric.Health.ApplicationHealthPolicy.DefaultServiceTypeHealthPolicy" /> zur Auswertung verwendet wird.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthPolicy.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthPolicy.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft eine Zeichenfolgendarstellung der Integritätsrichtlinie der Anwendung ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung einer anwendungsintegritäts-Richtlinie.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>