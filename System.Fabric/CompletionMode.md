<Type Name="CompletionMode" FullName="System.Fabric.CompletionMode">
  <TypeSignature Language="C#" Value="public enum CompletionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed CompletionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CompletionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum CompletionMode" />
  <TypeSignature Language="F#" Value="type CompletionMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Dies ist eine Enumeration, die verwendet werden, um anzugeben, wann die API abgeschlossen sein sollte. 
            </summary>
    <remarks>
            Die Werte geben an, ob die API abgeschlossen werden sollte, wenn die Anforderung für den Vorgang abgeschlossen ist, oder wenn der angeforderte Vorgang abgeschlossen wurde. Beispielsweise könnte eine Anforderung zum einen Knoten neu gestartet werden abschließen, wie schnell die Anforderung akzeptiert wird, oder wenn die API überprüfen kann, dass der Knoten neu gestartet wurde. Die eigentliche Überprüfung richtet sich nach der verwendeten API ab.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="DoNotVerify">
      <MemberSignature Language="C#" Value="DoNotVerify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode DoNotVerify = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.DoNotVerify" />
      <MemberSignature Language="VB.NET" Value="DoNotVerify" />
      <MemberSignature Language="F#" Value="DoNotVerify = 1" Usage="System.Fabric.CompletionMode.DoNotVerify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Abschluss der Aktion nicht überprüft werden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.CompletionMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Beendigungsmodus keinen gültigen Wert.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="Verify" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.CompletionMode Verify = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.CompletionMode.Verify" />
      <MemberSignature Language="VB.NET" Value="Verify" />
      <MemberSignature Language="F#" Value="Verify = 2" Usage="System.Fabric.CompletionMode.Verify" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CompletionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Vergewissern Sie sich den Abschluss der Aktion.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>