<Type Name="ScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.ScaleSettings">
  <TypeSignature Language="C#" Value="public class ScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleSettings" />
  <TypeSignature Language="F#" Value="type ScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Skalierungseinstellungen für den pool
            </summary>
    <remarks>
            Definiert die gewünschte Größe des Pools an. Dies kann entweder "FixedScale", wobei die angeforderte TargetDedicatedNodes festgelegt wird, oder "automatisch skalieren" der Formel definiert, welche die in regelmäßigen Abständen neu ausgewertet wird. Wenn diese Eigenschaft nicht angegeben ist, wird der Pool eine feste Skala mit 0 TargetDedicatedNodes aufweisen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ScaleSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleSettings (Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale = null, Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings fixedScale, class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings autoScale) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.#ctor(Microsoft.Azure.Management.Batch.Models.FixedScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional fixedScale As FixedScaleSettings = null, Optional autoScale As AutoScaleSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ScaleSettings : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleSettings -&gt; Microsoft.Azure.Management.Batch.Models.ScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.ScaleSettings (fixedScale, autoScale)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fixedScale" Type="Microsoft.Azure.Management.Batch.Models.FixedScaleSettings" />
        <Parameter Name="autoScale" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings" />
      </Parameters>
      <Docs>
        <param name="fixedScale">Feste skalierungseinstellungen für den Pool.</param>
        <param name="autoScale">Einstellungen für automatische Skalierung für den Pool.</param>
        <summary>
            Initialisiert eine neue Instanz der ScaleSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleSettings AutoScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoScale As AutoScaleSettings" />
      <MemberSignature Language="F#" Value="member this.AutoScale : Microsoft.Azure.Management.Batch.Models.AutoScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.AutoScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Einstellungen für automatische Skalierung für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und die FixedScale schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FixedScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.FixedScaleSettings FixedScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberSignature Language="VB.NET" Value="Public Property FixedScale As FixedScaleSettings" />
      <MemberSignature Language="F#" Value="member this.FixedScale : Microsoft.Azure.Management.Batch.Models.FixedScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ScaleSettings.FixedScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fixedScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.FixedScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest festen skalierungseinstellungen für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und die automatische Skalierung schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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