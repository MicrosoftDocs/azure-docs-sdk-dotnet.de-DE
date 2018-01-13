<Type Name="ApplicationTypeHealthPolicyMap" FullName="System.Fabric.Health.ApplicationTypeHealthPolicyMap">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypeHealthPolicyMap : System.Collections.Generic.Dictionary&lt;string,byte&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypeHealthPolicyMap extends System.Collections.Generic.Dictionary`2&lt;string, unsigned int8&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypeHealthPolicyMap&#xA;Inherits Dictionary(Of String, Byte)" />
  <TypeSignature Language="F#" Value="type ApplicationTypeHealthPolicyMap = class&#xA;    inherit Dictionary&lt;string, byte&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Byte&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Byte</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            Definiert eine Zuordnung mit "fehlerhaft" höchstprozentsätze-Anwendungen für bestimmte Anwendungstypen. 
            </para>
    </summary>
    <remarks>Die Zuordnung der Anwendungstyp-Integritätsrichtlinie kann während der Clusterintegritätsevaluierung verwendet werden, um spezielle Anwendungstypen zu beschreiben. Die Anwendungstypen, die in der Zuordnung enthaltenen werden ausgewertet, für den Prozentsatz enthalten in der Zuordnung, und nicht mit dem globalen <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />.
            Zu den Anwendungsbereichen von Anwendungstypen, die in der Zuordnung angegeben werden für den globalen Pool von Anwendungen nicht gezählt.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationTypeHealthPolicyMap ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            Instanziiert eine <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" /> Klasse.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (string appTypeName, byte value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(string appTypeName, unsigned int8 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.Add(System.String,System.Byte)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (appTypeName As String, value As Byte)" />
      <MemberSignature Language="F#" Value="override this.Add : string * byte -&gt; unit" Usage="applicationTypeHealthPolicyMap.Add (appTypeName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appTypeName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte" />
      </Parameters>
      <Docs>
        <param name="appTypeName">
          <para>Der Name des Anwendungstyps.</para>
        </param>
        <param name="value">
          <para>Die max Prozent "fehlerhaft" Anwendungen, das für die Anwendung vom Typ zulässig. Muss zwischen 0 und 100 liegen.</para>
        </param>
        <summary>
          <para>
            Fügt einen Eintrag in der Zuordnung für einen bestimmten Anwendungstyp mit max Prozentsatz fehlerhafter Anwendungen als Wert an.
            </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Prozentwert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationTypeHealthPolicyMap.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationTypeHealthPolicyMap.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>