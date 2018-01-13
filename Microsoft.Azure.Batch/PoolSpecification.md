<Type Name="PoolSpecification" FullName="Microsoft.Azure.Batch.PoolSpecification">
  <TypeSignature Language="C#" Value="public class PoolSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolSpecification" />
  <TypeSignature Language="F#" Value="type PoolSpecification = class&#xA;    interface ITransportObjectProvider&lt;PoolSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Spezifikation für einen Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.PoolSpecification" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Anwendungsverweise an Paket auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoScaleEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoScaleEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Größe des Pools mit der Zeit automatisch angepasst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Wenn "false" eines der <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> oder <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> ist eine erforderliche Eigenschaft.</para>
          <para>Bei "true", die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" /> ist eine erforderliche Eigenschaft. Der Pool wird automatisch entsprechend der Formel.</para>
          <para>Der Standardwert ist „false“.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Zeitintervall an, passen Sie die Poolgröße gemäß automatisch an die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert beträgt 15 Minuten. Der minimal zulässige Wert beträgt 5 Minuten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Formel für die gewünschte Anzahl von Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Für das Schreiben von Formeln für automatische Skalierung finden Sie unter https://azure.microsoft.com/documentation/articles/batch-automatic-scaling/. Diese Eigenschaft ist erforderlich, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true". Sie muss null sein, wenn AutoScaleEnabled auf "false" festgelegt ist.</para>
          <para>Die Formel wird auf Gültigkeit überprüft, bevor der Pool erstellt wird. Wenn die Formel nicht gültig ist, wird eine Ausnahme ausgelöst, wenn Sie versuchen, einen commit für die <see cref="T:Microsoft.Azure.Batch.PoolSpecification" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Batch.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" /> für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist mit sich gegenseitig ausschließende <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterComputeNodeCommunicationEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; InterComputeNodeCommunicationEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property InterComputeNodeCommunicationEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.InterComputeNodeCommunicationEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.InterComputeNodeCommunicationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der Pool direkten Kommunikation zwischen der Serverknoten zulässt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Aktivieren der Kommunikation zwischen den Knoten schränkt die maximale Größe des Pools aufgrund von Einschränkungen der Bereitstellung auf den Knoten des Pools. Dies kann im Pool nicht die gewünschte Größe erreichen führen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerComputeNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerComputeNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerComputeNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerComputeNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerComputeNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.MaxTasksPerComputeNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist 1. Der maximale Wert dieser Einstellung hängt von der Größe der Serverknoten im Pool (die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" /> Eigenschaft).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Batch.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Netzwerkkonfiguration des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ResizeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ResizeTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ResizeTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ResizeTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.ResizeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Timeout für die Zuweisung von Serverknoten in den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Dieses Timeout gilt nur für die manuelle Skalierung. Es hat keine Wirkung, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true".</para>
          <para>Der Standardwert beträgt 15 Minuten. Der Mindestwert ist 5 Minuten.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen. Der Task ausgeführt wird, wenn der Knoten hinzugefügt wird, an den Pool oder der Knoten neu gestartet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicated As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicated : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Obsolete after 05/2017, use TargetDedicatedComputeNodes instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Diese Eigenschaft ist ein Alias für <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> und wird nur für Abwärtskompatibilität unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDedicatedComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetDedicatedComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetDedicatedComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDedicatedComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetDedicatedComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von dedizierten Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true". Mindestens eine dieser Eigenschaft und <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" /> muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> lautet "false". Wenn nicht angegeben, lautet der Standardwert 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLowPriorityComputeNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetLowPriorityComputeNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetLowPriorityComputeNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLowPriorityComputeNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetLowPriorityComputeNodes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TargetLowPriorityComputeNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die gewünschte Anzahl von Serverknoten mit niedriger Priorität im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Einstellung kann nicht angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> festgelegt ist auf "true". Mindestens eine der <see cref="P:Microsoft.Azure.Batch.PoolSpecification.TargetDedicatedComputeNodes" /> und diese Eigenschaft muss angegeben werden, wenn <see cref="P:Microsoft.Azure.Batch.PoolSpecification.AutoScaleEnabled" /> lautet "false". Wenn nicht angegeben, lautet der Standardwert 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Batch.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten im Pool verteilt sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Batch.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" /> des Pools.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist mit sich gegenseitig ausschließende <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string with get, set" Usage="Microsoft.Azure.Batch.PoolSpecification.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der virtuellen Computer im Pool.  Alle virtuellen Computer in einem Pool haben die gleiche Größe.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit erstellt eine <see cref="P:Microsoft.Azure.Batch.PoolSpecification.CloudServiceConfiguration" />), finden Sie unter https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/. Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</para>
          <para>Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images von virtuellen Maschinen Marketplace (mit erstellten Ressourcenpools einer <see cref="P:Microsoft.Azure.Batch.PoolSpecification.VirtualMachineConfiguration" />) finden Sie unter https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ oder https:// Azure.Microsoft.com/Documentation/articles/Virtual-Machines-Windows-sizes/. Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (z. B. STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>