<Type Name="RollingUpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradePolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Konfigurationsparameter, die beim Ausführen eines parallelen Upgrades verwendet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RollingUpgradePolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicy (Nullable&lt;int&gt; maxBatchInstancePercent = null, Nullable&lt;int&gt; maxUnhealthyInstancePercent = null, Nullable&lt;int&gt; maxUnhealthyUpgradedInstancePercent = null, string pauseTimeBetweenBatches = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; maxBatchInstancePercent, valuetype System.Nullable`1&lt;int32&gt; maxUnhealthyInstancePercent, valuetype System.Nullable`1&lt;int32&gt; maxUnhealthyUpgradedInstancePercent, string pauseTimeBetweenBatches) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxBatchInstancePercent As Nullable(Of Integer) = null, Optional maxUnhealthyInstancePercent As Nullable(Of Integer) = null, Optional maxUnhealthyUpgradedInstancePercent As Nullable(Of Integer) = null, Optional pauseTimeBetweenBatches As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy : Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy" Usage="new Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy (maxBatchInstancePercent, maxUnhealthyInstancePercent, maxUnhealthyUpgradedInstancePercent, pauseTimeBetweenBatches)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxBatchInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxUnhealthyInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxUnhealthyUpgradedInstancePercent" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="pauseTimeBetweenBatches" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="maxBatchInstancePercent">Der maximale Prozentsatz der gesamten virtuellen Computerinstanzen, die von der parallelen Upgrades in einem Batch gleichzeitig aktualisiert werden. Da dies ein Maximum ist, können "fehlerhaft" Instanzen in der vorherigen oder zukünftige Batches den Prozentsatz der Instanzen in einem Batch zu verringern, um sicherzustellen, dass höhere Zuverlässigkeit verursachen. Der Standardwert für diesen Parameter ist 20 %.</param>
        <param name="maxUnhealthyInstancePercent">Der maximale Prozentsatz der insgesamt VM-Instanzen in der Menge von Skalierung, die gleichzeitig "fehlerhaft", entweder als Ergebnis der zu aktualisierenden oder in einem fehlerhaften Zustand von der virtuellen Maschine Systemdiagnosen gefunden wird, bevor das parallele Upgrade abgebrochen werden kann. Diese Einschränkung wird vor Beginn jeder Batch überprüft werden. Der Standardwert für diesen Parameter ist 20 %.</param>
        <param name="maxUnhealthyUpgradedInstancePercent">Der maximale Prozentsatz der aktualisierten virtuellen Computerinstanzen, die in einem fehlerhaften Zustand befinden. Diese Überprüfung erfolgt nach dem Upgrade von jedem Batch. Wenn dieser Prozentsatz jemals überschritten wird, bricht das parallele Update ab. Der Standardwert für diesen Parameter ist 20 %.</param>
        <param name="pauseTimeBetweenBatches">Die Wartezeit zwischen Durchführung des Updates für alle virtuellen Computer in einem Batch aus, und starten den nächsten Batch. Die Dauer sollte im ISO 8601-Format angegeben werden. Der Standardwert ist 0 Sekunden (PT0S).</param>
        <summary>
            Initialisiert eine neue Instanz der RollingUpgradePolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxBatchInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxBatchInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxBatchInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxBatchInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxBatchInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxBatchInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den maximalen Prozentsatz der gesamten virtuellen Computerinstanzen, die von der parallelen Upgrades in einem Batch gleichzeitig aktualisiert werden. Da dies ein Maximum ist, können "fehlerhaft" Instanzen in der vorherigen oder zukünftige Batches den Prozentsatz der Instanzen in einem Batch zu verringern, um sicherzustellen, dass höhere Zuverlässigkeit verursachen. Der Standardwert für diesen Parameter ist 20 %.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxUnhealthyInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxUnhealthyInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxUnhealthyInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxUnhealthyInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxUnhealthyInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxUnhealthyInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den maximalen Prozentsatz der gesamten VM-Instanzen in der Menge von Skalierung, die gleichzeitig "fehlerhaft", entweder als Ergebnis der zu aktualisierenden oder in einem fehlerhaften Zustand gefunden wird, indem Sie die virtuelle Maschine Systemdiagnosen vor den gleitenden werden können Upgrade bricht ab. Diese Einschränkung wird vor Beginn jeder Batch überprüft werden. Der Standardwert für diesen Parameter ist 20 %.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxUnhealthyUpgradedInstancePercent">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxUnhealthyUpgradedInstancePercent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxUnhealthyUpgradedInstancePercent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyUpgradedInstancePercent" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxUnhealthyUpgradedInstancePercent As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxUnhealthyUpgradedInstancePercent : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.MaxUnhealthyUpgradedInstancePercent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxUnhealthyUpgradedInstancePercent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den maximalen Prozentsatz der aktualisierten virtuellen Computerinstanzen, die in einem fehlerhaften Zustand befinden. Diese Überprüfung erfolgt nach dem Upgrade von jedem Batch. Wenn dieser Prozentsatz jemals überschritten wird, bricht das parallele Update ab. Der Standardwert für diesen Parameter ist 20 %.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PauseTimeBetweenBatches">
      <MemberSignature Language="C#" Value="public string PauseTimeBetweenBatches { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PauseTimeBetweenBatches" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.PauseTimeBetweenBatches" />
      <MemberSignature Language="VB.NET" Value="Public Property PauseTimeBetweenBatches As String" />
      <MemberSignature Language="F#" Value="member this.PauseTimeBetweenBatches : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.PauseTimeBetweenBatches" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pauseTimeBetweenBatches")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Wartezeit zwischen Durchführung des Updates für alle virtuellen Computer in einem Batch aus, und starten den nächsten Batch. Die Dauer sollte im ISO 8601-Format angegeben werden. Der Standardwert ist 0 Sekunden (PT0S).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.RollingUpgradePolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="rollingUpgradePolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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