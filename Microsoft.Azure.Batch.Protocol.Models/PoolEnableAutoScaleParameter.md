<Type Name="PoolEnableAutoScaleParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter">
  <TypeSignature Language="C#" Value="public class PoolEnableAutoScaleParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEnableAutoScaleParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEnableAutoScaleParameter" />
  <TypeSignature Language="F#" Value="type PoolEnableAutoScaleParameter = class" />
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
            Optionen für das Aktivieren der automatischen Skalierung für einen Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEnableAutoScaleParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.#ctor" />
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
            Initialisiert eine neue Instanz der PoolEnableAutoScaleParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEnableAutoScaleParameter (string autoScaleFormula = null, Nullable&lt;TimeSpan&gt; autoScaleEvaluationInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string autoScaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoScaleEvaluationInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.#ctor(System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional autoScaleFormula As String = null, Optional autoScaleEvaluationInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter : string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter (autoScaleFormula, autoScaleEvaluationInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="autoScaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="autoScaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <param name="autoScaleEvaluationInterval">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolEnableAutoScaleParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleEvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoScaleEvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoScaleEvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleEvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleEvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoScaleEvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleEvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleEvaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall an, die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert beträgt 15 Minuten. Die minimale und maximale Wert sind 5 Minuten und 168 Stunden. Wenn Sie einen Wert kleiner als 5 Minuten größer oder gleich 168 Stunden angeben, weist der Batch-Dienst die Anforderung mit einem Fehler der ungültige Eigenschaft-Wert; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Wenn Sie ein neues Intervall angeben, der Zeitplan des vorhandenen automatische Skalierung Auswertung wird beendet, und ein neue automatische Skalierung Zeitplan gestartet wird, mit der Startzeit wird die Zeit, wenn diese Anforderung ausgestellt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter.AutoScaleFormula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScaleFormula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Formel für die gewünschte Anzahl von Serverknoten im Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Formel wird auf Gültigkeit überprüft, bevor es an den Pool angewendet wird. Wenn die Formel nicht gültig ist, weist der Batch-Dienst die Anforderung mit detaillierten Fehlerinformationen zurück. Weitere Informationen zum Angeben dieser Formel finden Sie unter automatisch skalieren Serverknoten in einem Azure Batch-Pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>