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
            <span data-ttu-id="63699-101">Definiert eine Zuordnung mit "fehlerhaft" höchstprozentsätze-Anwendungen für bestimmte Anwendungstypen.</span><span class="sxs-lookup"><span data-stu-id="63699-101">Defines a map with max percentages unhealthy applications for specific application types.</span></span> 
            </para>
    </summary>
    <remarks><span data-ttu-id="63699-102">Die Zuordnung der Anwendungstyp-Integritätsrichtlinie kann während der Clusterintegritätsevaluierung verwendet werden, um spezielle Anwendungstypen zu beschreiben.</span><span class="sxs-lookup"><span data-stu-id="63699-102">The application type health policy map can be used during cluster health evaluation to describe special application types.</span></span> <span data-ttu-id="63699-103">Die Anwendungstypen, die in der Zuordnung enthaltenen werden ausgewertet, für den Prozentsatz enthalten in der Zuordnung, und nicht mit dem globalen <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />.</span><span class="sxs-lookup"><span data-stu-id="63699-103">The application types included in the map are evaluated against the percentage included in the map, and not with the global <see cref="P:System.Fabric.Health.ClusterHealthPolicy.MaxPercentUnhealthyApplications" />.</span></span>
            <span data-ttu-id="63699-104">Zu den Anwendungsbereichen von Anwendungstypen, die in der Zuordnung angegeben werden für den globalen Pool von Anwendungen nicht gezählt.</span><span class="sxs-lookup"><span data-stu-id="63699-104">The applications of application types specified in the map are not counted against the global pool of applications.</span></span></remarks>
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
            <span data-ttu-id="63699-105">Instanziiert eine <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="63699-105">Instantiates an <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" /> class.</span></span>
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
          <para><span data-ttu-id="63699-106">Der Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="63699-106">The application type name.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="63699-107">Die max Prozent "fehlerhaft" Anwendungen, das für die Anwendung vom Typ zulässig.</span><span class="sxs-lookup"><span data-stu-id="63699-107">The max percent unhealthy applications allowed for the application type.</span></span> <span data-ttu-id="63699-108">Muss zwischen 0 und 100 liegen.</span><span class="sxs-lookup"><span data-stu-id="63699-108">Must be between 0 and 100.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="63699-109">Fügt einen Eintrag in der Zuordnung für einen bestimmten Anwendungstyp mit max Prozentsatz fehlerhafter Anwendungen als Wert an.</span><span class="sxs-lookup"><span data-stu-id="63699-109">Adds an entry in the map for a specific application type, with max percent unhealthy applications as value.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="63699-110">Der angegebene Prozentwert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="63699-110">The specified percentage value was outside the range of integer values from zero to 100.</span></span></para>
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
            <span data-ttu-id="63699-111">Ruft eine Zeichenfolgendarstellung der <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span><span class="sxs-lookup"><span data-stu-id="63699-111">Gets a string representation of the <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span></span>
            </summary>
        <returns><span data-ttu-id="63699-112">Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span><span class="sxs-lookup"><span data-stu-id="63699-112">A string representation of the <see cref="T:System.Fabric.Health.ApplicationTypeHealthPolicyMap" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>