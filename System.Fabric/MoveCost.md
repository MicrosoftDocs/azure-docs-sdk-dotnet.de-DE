<Type Name="MoveCost" FullName="System.Fabric.MoveCost">
  <TypeSignature Language="C#" Value="public enum MoveCost" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MoveCost extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.MoveCost" />
  <TypeSignature Language="VB.NET" Value="Public Enum MoveCost" />
  <TypeSignature Language="F#" Value="type MoveCost = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Beschreibt die Kosten für die Verschiebung eines Replikats an.</para>
    </summary>
    <remarks>
            Wenn eine neue Instanz der Replikat- oder Diensts erstellt wird erhalten sie einen Standardwert für Move Kosten. Dieser Wert wird basierend auf den Dienst ausgewählt: <list type="bullet"> <item> <description>für Replikate oder Instanzen von Standard-Dienste standardmäßig verschieben Kosten Wert <see cref="F:System.Fabric.MoveCost.Zero" />, was bedeutet, dass diese Replikate verschieben frei ist.</description> </item> <item> <description>Für Replikate oder andere Dienste Standard-Instanzen verschieben Kosten werden <see cref="F:System.Fabric.MoveCost.Low" />.</description></item></list></remarks>
  </Docs>
  <Members>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="High" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost High = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.High" />
      <MemberSignature Language="VB.NET" Value="High" />
      <MemberSignature Language="F#" Value="High = 3" Usage="System.Fabric.MoveCost.High" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, die Kosten für die Verschiebung eines Replikats als hoch.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="Low" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Low = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Low" />
      <MemberSignature Language="VB.NET" Value="Low" />
      <MemberSignature Language="F#" Value="Low = 1" Usage="System.Fabric.MoveCost.Low" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, die Kosten für die Verschiebung eines Replikats als niedrig.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Medium">
      <MemberSignature Language="C#" Value="Medium" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Medium = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Medium" />
      <MemberSignature Language="VB.NET" Value="Medium" />
      <MemberSignature Language="F#" Value="Medium = 2" Usage="System.Fabric.MoveCost.Medium" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, die Move Kosten für ein Replikat als Mittel.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Zero">
      <MemberSignature Language="C#" Value="Zero" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.MoveCost Zero = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.MoveCost.Zero" />
      <MemberSignature Language="VB.NET" Value="Zero" />
      <MemberSignature Language="F#" Value="Zero = 0" Usage="System.Fabric.MoveCost.Zero" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, die Kosten für die Verschiebung eines Replikats als 0 (null).</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>