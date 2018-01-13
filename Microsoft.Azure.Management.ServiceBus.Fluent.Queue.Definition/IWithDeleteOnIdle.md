<Type Name="IWithDeleteOnIdle" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithDeleteOnIdle">
  <TypeSignature Language="C#" Value="public interface IWithDeleteOnIdle" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDeleteOnIdle" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithDeleteOnIdle" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDeleteOnIdle" />
  <TypeSignature Language="F#" Value="type IWithDeleteOnIdle = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Warteschlange Definition ermöglicht automatische definieren löschen Verhalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDeleteOnIdleDurationInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithDeleteOnIdleDurationInMinutes (int durationInMinutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithDeleteOnIdleDurationInMinutes(int32 durationInMinutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDeleteOnIdleDurationInMinutes (durationInMinutes As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDeleteOnIdleDurationInMinutes : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithDeleteOnIdle.WithDeleteOnIdleDurationInMinutes durationInMinutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="durationInMinutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="durationInMinutes">Die Leerlaufzeit in Minuten.</param>
        <summary>
            Das im Leerlauf Intervall, nach dem die Warteschlange automatisch gelöscht wird.
            Hinweis: es sei denn, sie explizit außer Kraft gesetzt wird das standardmäßige löschen Leerlaufdauer ist unendlich (TimeSpan.Max).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Warteschlangendefinition.</return>
      </Docs>
    </Member>
  </Members>
</Type>