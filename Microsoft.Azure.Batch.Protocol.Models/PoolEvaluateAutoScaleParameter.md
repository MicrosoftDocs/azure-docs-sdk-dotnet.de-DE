<Type Name="PoolEvaluateAutoScaleParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter">
  <TypeSignature Language="C#" Value="public class PoolEvaluateAutoScaleParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolEvaluateAutoScaleParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolEvaluateAutoScaleParameter" />
  <TypeSignature Language="F#" Value="type PoolEvaluateAutoScaleParameter = class" />
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
            Optionen für die Bewertung einer Formel für automatische Skalierung für einen Pool.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEvaluateAutoScaleParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter.#ctor" />
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
            Initialisiert eine neue Instanz der PoolEvaluateAutoScaleParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolEvaluateAutoScaleParameter (string autoScaleFormula);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string autoScaleFormula) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (autoScaleFormula As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter : string -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter autoScaleFormula" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="autoScaleFormula" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="autoScaleFormula">Die Formel für die gewünschte Anzahl von Serverknoten im Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolEvaluateAutoScaleParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleFormula">
      <MemberSignature Language="C#" Value="public string AutoScaleFormula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoScaleFormula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter.AutoScaleFormula" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScaleFormula As String" />
      <MemberSignature Language="F#" Value="member this.AutoScaleFormula : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter.AutoScaleFormula" />
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
            Die Formel überprüft wurde und seine Ergebnisse berechnet, jedoch nicht an den Pool angewendet wird. Um die Formel für den Pool anzuwenden, "Aktivieren der automatischen Skalierung für einen Pool". Weitere Informationen zum Angeben dieser Formel finden Sie unter automatisch skalieren Serverknoten in einem Azure Batch-Pool (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolEvaluateAutoScaleParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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